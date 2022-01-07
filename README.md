# OSCP-Notes
Adding notes on some machine I will be hacking for my OSCP Prep

directory bruteforcing
```
python3 ~/Desktop/tools/dirsearch/dirsearch.py -u http://10.10.84.74 -e php,html,txt,pdf,js,css,bak,old,asp,aspx
dirb http://10.10.84.74
nikto -h http://10.10.84.74/
```

