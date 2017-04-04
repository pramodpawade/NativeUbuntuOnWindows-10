#Run the native Ubuntu desktop on Windows 10#

Microsoft built new infrastructure within Windows – the Windows Subsystem for Linux (WSL) – upon which Microsoft run a genuine Ubuntu user-mode image provided by their partners over at Canonical, creators of Ubuntu Linux. You can now run Bash scripts, Linux command-line tools like sed, awk, grep, and you can even try Linux-first tools like Ruby, Git, Python, etc. directly on Windows. You can also access your Windows filesystem from within Bash allowing you to work on the same set of files using your preferred Windows tools or Linux command-line tools Bash on Windows provides developers with a familiar Bash shell and Linux environment in which you can run most Linux command-line tools, directly on Windows, UNMODIFIED, without needing an entire Linux virtual machine! Bash/WSL allows you to:

Run common command-line utilities such as grep, sed, awk, etc. delivered by an
Use the Linux-compatible filesystem & heirarchy and access fixed Windows storage mounted under /mnt/...
Run Bash shell scripts and Linux command-line apps. including o	Tools: vim, emacs, tmux o Languages: Javascript/node.js, Ruby, Python, C/C++, C# & F#, Rust, Go, etc. o	Services: sshd, MySQL, Apache, lighttpd,
Install additional Linux tools using apt
Invoke Windows applications from within Bash
Invoke Linux applications from within Windows! Bash on Windows runs Ubuntu user-mode binaries provided by Canonical. This means the command-line utilities are the same as those that run within a native Ubuntu environment.

To Learn more please go through below blog from Microsoft
https://blogs.msdn.microsoft.com/commandline/learn-about-bash-on-windows-subsystem-for-linux/

For Installation, please follow - https://msdn.microsoft.com/en-us/commandline/wsl/install_guide

Happy Sharing!!
