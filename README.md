# ios-security-testing-how-to

*Pen Testing or Security Testing:* Security testing is about finding security flow in the app. In security testing we try to hack the app and in some cases seach in the source code(white box) to find any potential secury flaw. We try to find security flow in 7 different areas: 

1. Basic Security Flaw: Check very basic but common some flaws like revealing some api key or some important data in source code.
1. Data Storage: Common data Storage vulnearablities are like keeping important data unencrypted or leaking internal data in some way.
2. Authentication: Vulnearibilities like if it is possible some way to bypass the authentication process or issues related to session data.
3. Network: Get unauthorized data from the Network with SQL injection or in some other way.
4. Cryptographic: Issues in using vulnearable or unproper criptographic algorithms.
5. Platform: Issues in third party library and proper usage of system resources.
6. Anti Reverse Engineering: For sensitive apps, if necessary anti reverse engineering measures are taken.

Some of the common approaches are:
Black box: You have no idea about the internals of the app. Try to hack like some random app.
Gray box: You have some idea about the architecture and about the app. But you don't have the source code.
White box: You have full source code. Easier to find vulnearability in limited time frame.


## Courses to follow:
This two below courses can give some idea about iOS Pen testing and the tools that are use.

* https://www.udemy.com/course/hacking-and-pentesting-ios-applications
* https://www.youtube.com/watch?v=2CKrw7ErzCY&t=3565s

## Book to read:
OWASP Mobile Security Testing Guide is a great book to understand every details and steps about ios pen testing. There are so much details and so much to learn. A must read. 

* https://github.com/OWASP/owasp-mstg

## Tools to use
* Checkra1n: Very popular jail break tool. Works devices lower than iPhone X. Easily un-jailbreak the device. 
* Cydia: Most popular Appstore for jailed broken device.
* OpenSSH: SSH client for mobile. Helps to run command on mobile from computer over SSH protocol.
* BurpSuite: Favorite proxy tool. Used to watch network communication and run different network hacking techniques.
* MobSF: Automated security testing tool.
* Frida + Objection: Runtime mobile exploration toolkit, powered by Frida, built to help you assess the security posture of your mobile applications. Can do tasks like, Bypass SSL pinning, dump keychains, performing memory related tasks, explore and manipulate objects on the heap. 
* SSL Kill Switch: Bypass SSL pinning
* Hopper: This is a disassembler and reverse engineering tool. This tool let you disassemble, decompile and debug your applications.
