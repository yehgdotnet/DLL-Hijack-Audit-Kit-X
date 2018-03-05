
A Slightly Modified version of HDMore's DLL Hijack Audit Kit

By default, HDM's DLLHijackAuditKit scans all associated file extensions with all installed applications in default timer of 3 seconds.

DLLHijackAuditor from SecurityXploded is great for targetting only one application. However, according to our testing, it sometimes misses flaws.

So, we tried to save time by adding timer support and regex support to our favorite HDM's DLLHijackAuditKit.

Note that dll files in DLLHijackAuditKit will be detected as virus/trojan as they are generated using Metasploit. We protected it with password - yehg.net

Platform: Windows 2K3/XP

Language: VBScript