每次装完 Gentoo Linux 都需要重新写 package.use, package.accept_keywords, package.license 这些，太难受了。我选择将它们备份一下。

我选择了 LLVM/systemd profile，全局 thinlto 编译，开启了 luks2 硬盘加密和安全启动。

我现在正在尝试使用 [Clang 的 CFI](https://clang.llvm.org/docs/ControlFlowIntegrity.html) 编译，目前只尝试了部分有图形化界面的软件，如 mpv、sway 等，具体哪些软件用了，我把它记在了 package.env/test4cfi 里了
