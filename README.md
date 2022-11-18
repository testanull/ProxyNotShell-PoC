### Working PoC for CVE-2022-41040 and CVE-2022-41082 (A.K.A ProxyNotShell)

Requirement:

- pip install requests_ntlm2 requests

Usage:
```
python poc_aug3.py <host> <username> <password> <command>
```

Creds:

- ProxyShell PoC script from: https://blog.viettelcybersecurity.com/pwn2own-2021-microsoft-exchange-exploit-chain/

- Gtsc's blog post

- https://www.zerodayinitiative.com/blog/2022/11/14/control-your-types-or-get-pwned-remote-code-execution-in-exchange-powershell-backend
