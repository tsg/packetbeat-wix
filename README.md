# Wix files for Packetbeat

WIP, likely to be deleted as Packetbeat will get a better installer.

To build the msi:

    j2 packetbeat.wxs packetbeat_in.yml > packetbeat-1.0.0-beta2.wxs
    wixl -D SourceDir=`pwd` -v packetbeat-1.0.0-beta2.wxs

For the `j2` command above: `pip install -r requirements.txt`.
