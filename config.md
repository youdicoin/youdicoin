git add .
git commit -m ‘message-commit’
git push origin master

- Followed guide: https://bitcointalk.org/index.php?topic=3345808.msg35016844#msg35016844
- Replace texts: http://cybernetnews.com/find-replace-multiple-files/

# Data edited from source code of bitcoincore project  

- nDefaultPort = 8383; in /src/chainparams.cpp file

- pchMessageStart[0] = 0x83;
  pchMessageStart[1] = 0xe5;
  pchMessageStart[2] = 0xa3;
  pchMessageStart[3] = 0xa3;

  in /src/chainparams.cpp file
