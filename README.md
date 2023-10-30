# My Powerhub Module Collection


Pretty much all scripts, binaries, etc are taken from other sources.

Module name | Version date | Description | Example usage
---|---|---|---
[PowerUp.ps1](https://github.com/PowerShellMafia/PowerSploit/blob/master/Privesc/PowerUp.ps1) | 2017-09-17 | Windows privilege escalation script | TODO
[Invoke-ShareFinder.ps1](https://github.com/darkoperator/Veil-PowerView/blob/master/PowerView/functions/Invoke-ShareFinder.ps1) | 2014-12-03 | Find accessible SMB shares | TODO
[PrivescCheck.ps1](https://github.com/itm4n/PrivescCheck/blob/master/PrivescCheck.ps1) | 2023-10-24 | Windows privilege escalation | Invoke-PrivescCheck -Extended -Report PrivescCheck_%COMPUTERNAME% -Format TXT,CSV,HTML,XML

TODO:
- winPEAS
- Switch to updated powerup version like https://github.com/AdrianVollmer/PowerSploit/commits/master/Privesc/PowerUp.ps1?
- sharphound exe/ps1
- something for lsass dump
- mimikatz?


## TODO: Compile

I should figure out how to compile them, since they have no public builds:

- https://github.com/GhostPack/Certify
- https://github.com/GhostPack/Seatbelt
