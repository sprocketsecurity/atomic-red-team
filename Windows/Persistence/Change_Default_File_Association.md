# Change Default File Association

MITRE ATT&CK Technique: [T1042](https://attack.mitre.org/wiki/Technique/T1042)

## User file association preferences are stored under

    [HKEY_CURRENT_USER]\Software\Microsoft\Windows\CurrentVersion\Explorer\FileExts

Changes to a user's preference will occur under this entry's subkeys.

## Change open program with ftype

    ftype txtfile="C:\windows\system32\cmd.exe"
