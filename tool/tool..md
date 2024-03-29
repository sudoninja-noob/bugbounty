Total virus
https://www.virustotal.com/gui/home/search


## web tool

   **Burp Suite:** This is the most popular proxy in web hacking circles due to its cross-platform nature and extensive featureset. See       our playlist to make the most of it.
    **mitmproxy:** This is an open-source proxy written in Python. Not recommended for beginners, but this can be a powerful tool.
    **sqlmap:** This allows for easy discovery and exploitation of SQL injection vulnerabilities. It will not catch every bug or even
    be able to exploit some known SQLi bugs. What it will do is make your life much easier in the 80% of cases it will work for.
    **SSL Labs Server Test:** This is an easy to use webapp for testing the SSL configuration of web servers.
    **DirBuster:** This is useful for finding hidden files and directories on web servers.
    **Nikto2:** Like DirBuster, but also does some basic checks for known vulnerabilities.
    **lazyrecon:** This is an assembled collection of tools for performing recon.

## Mobie Haacking tool

**Burp Suite:** This is the most popular proxy in web hacking circles due to its cross-platform nature and extensive featureset. See our playlist to make the most of it.
**Frida:** This is an instrumentation system allowing injection of JavaScript or native libraries into arbitrary mobile applications on iOS and Android. In essence, it makes it painless to change, enhance, or disable functionality in applications.
**dex2jar:** Converts dex code (Android bytecode) into Java JAR files for manipulation or decompilation.
**JD-GUI:** This is a Java decompiler, useful after dex2jar for easy analysis of Android apps.
**dotPeek:** A .NET decompiler, for use with Xamarin Android applications.

## Desktop/embedded hacking tools

**IDA Pro and Hex-Rays Decompiler:** IDA is the absolute gold standard for disassemblers and its decompiler plugins are the gold standard for decompilation. It is a wonderful tool with support for nearly every obscure platform and an extensive (if confusing) SDK to add nearly any feature you can imagine. However, its price makes it difficult to justify.
**Hopper:** This is a fantastic, low-cost disassembler and decompiler that runs on macOS and Linux. While it's no replacement for IDA, it is a great choice for most applications.
**Binary Ninja:** Another low-cost alternative to IDA. Its API is perhaps the most powerful of the three for automating analysis of code.
**Radare2:** This is a set of tools for doing analysis of binaries. It includes everything from disassembly to debugging and more.
**PE Explorer:** This is a great tool for analyzing the PE binaries used on Windows. It allows for exploration of the structures of the executable itself, as well as resources.
**dotPeek:** A powerful decompiler for .NET assemblies.
**PEiD:** Tool for detecting cryptors, packers, and encryption routines in Windows PE binaries.
**Unicorn Engine:** This is a library rather than a standalone tool, but it makes writing quick emulators a breeze. Particularly useful for reverse-engineering.
**american fuzzy lop:** AFL is an extremely powerful fuzzer, enabling detection of complicated bugs in many applications and libraries.
**Binwalk:** Used for firmware analysis and extraction. This is primarily useful for embedded Linux devices.
**GNU strings:** Finds strings in arbitrary binaries. While not strictly for reverse-engineering, it is among the most useful tools around.
**HxD (Windows) 0xED (macOS):** These are graphical hex editors, useful for analysis and manipulation of files and block devices.
**QEMU:** An emulator and virtual machine supporting a large number of systems/architectures. This makes it useful for things like running embedded firmware, but also includes debugging facilities that make it an optimal tool for hacking. Can be combined with AFL for fuzzing of binaries that aren't for your native architecture


## Programming languages
**Python and Ruby:** Useful for automation and quick testing and analysis, particularly for web hacking.
**JavaScript:** Can be used for the same tasks as Python and Ruby (albeit with fewer relevant libraries), but mostly useful to know for analysis of code on the web, as well as exploitation.
**Objective-C and Swift:** The ability to read these will be essential if you plan to do source code review of iOS applications.
**Java and Kotlin:** The ability to read these will be essential if you plan to do source code review of Android applications. Java is produced by decompilers for Android applications, which allows you to read code (roughly) equivalent to the original source, even when you only have a compiled application.
**AArch64 assembly:** For advanced embedded and mobile hacking, understanding the very lowest level of abstraction is essential.
