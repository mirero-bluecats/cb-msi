 $env:GITHUB_VERSION="v0.0.0"; $env:BLUECATS_HUB_VERSION="v0.3.2"; ./build build --cid v0.3.2 --bitness x64 collectbeat
 
 .\logstash --path.settings "C:\ProgramData\Mirero\BLUE CATS\collectbeat\config" --path.data "C:\ProgramData\Mirero\BLUE CATS\collectbeat\data"  --path.logs "C:\ProgramData\Mirero\BLUE CATS\collectbeat\logs"