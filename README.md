echo "# Belle" >> README.md

this is the prcess of how to download data from illumina basespapce by linux command.

step1: download the latest CLI release using your web browser
```
wget "https://launch.basespace.illumina.com/CLI/latest/amd64-linux/bs" ## output is in /workspace/rsrch2/common_data/illumina_NGS_101723
chmod u+x bs
```

step2: Authenticate
```
bs auth #it will open a browser and click with corresponding options and close that page.
```

step3 : Inspect the token to see what it does:
bs whoami 
![image](https://github.com/ww1021pp/Belle/assets/60449311/9b8648f6-8b13-4735-9b09-8c4e798314a8)

step4: list all projects under the related account

![image](https://github.com/ww1021pp/Belle/assets/60449311/2c8978ef-9d35-49e9-87ba-c26706fa8b9d)

step5 : filter project by project name
![image](https://github.com/ww1021pp/Belle/assets/60449311/42275d74-3407-42a7-aa0a-3bd741b2e9c8)

step6: download project by project ID
![image](https://github.com/ww1021pp/Belle/assets/60449311/c2f4467c-e4e3-4480-b59b-826fbd9a81b7)
