Windows Server is a brand name for a group of server operating systems.

How to convert Windows Server 2012 R2 Standard Evaluation into Full version

1) Open cdm as Administrator
2) Digit:
	DISM /online /Get-TargetEditions
3) Press Enter
4) Digit:
	DISM /online /Set-Edition:ServerStandard /ProductKey:DBGBW-NPF86-BJVTX-K3WKJ-MTB6V /AcceptEula
5) Press Enter and wait
6) Reboot the system

Now you have converted the evaluation version into full ones.

——————————————

How to convert Windows Server 2012 R2 Datacenter Evaluation into Full version

1) Open cdm as Administrator
2) Digit:
	DISM /online /Get-TargetEditions
3) Press Enter
4) Digit:
	DISM /online /Set-Edition:ServerStandard /ProductKey:Y4TGP-NPTV9-HTC2H-7MGQ3-DV4TW /AcceptEula
5) Press Enter and wait
6) Reboot the system

Now you have converted the evaluation version into full ones.



This procedure works also in Windows Server 2012 but you need to change this keys.

To definitively activate the system you need the Microsoft Toolkit.
