# CVE-2024-38077-EXP

基于[伪代码](https://sites.google.com/site/zhiniangpeng/blogs/MadLicense)后修复的代码。


# 有效范围

EXP：Windows Server 2025

POC：08-25

# 使用

```
options:
  -h, --help            show this help message and exit
  --target_ip TARGET_IP
                        Target IP, eg: 192.168.120.1
  --evil_ip EVIL_IP     Evil IP, eg: 192.168.120.2
  --evil_dll_path EVIL_DLL_PATH
                        Evil dll path, eg: \smb\evil_dll.dll
  --check_vuln_exist CHECK_VULN_EXIST
                        Check vulnerability exist before exploit
```

# 参考

https://sites.google.com/site/zhiniangpeng/blogs/MadLicense