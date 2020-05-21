asnp citrix*
Get-XdAuthentication
$iconfile= "C:\temp\cross.ico"
$ctxcloudApp= "App01"
$icon=Get-BrokerIcon -FileName $iconfile  |New-BrokerIcon | Select-Object Uid
Get-BrokerApplication -name $ctxcloudapp | Set-BrokerApplication -IconUid $icon.Uid 
