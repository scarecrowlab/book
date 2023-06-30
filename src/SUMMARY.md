# Rust 编程语言

[Rust 编程语言](title-page.md)
[前续](foreword.md)
[简介](ch00-00-introduction.md)

## 开始

- [开始](ch01-00-getting-started.md)
    - [安装](ch01-01-installation.md)
    - [你好世界](ch01-02-hello-world.md)

- [猜谜游戏](ch02-00-guessing-game-tutorial.md)

- [常用编程概念](ch03-00-common-programming-concepts.md)
    - [变量和不变](ch03-01-variables-and-mutability.md)
    - [数据类型](ch03-02-data-types.md)
    - [函数](ch03-03-how-functions-work.md)
    - [注释](ch03-04-comments.md)
    - [流程控制](ch03-05-control-flow.md)

- [理解所有权](ch04-00-understanding-ownership.md)
    - [什么是所有权?](ch04-01-what-is-ownership.md)
    - [引用和借用](ch04-02-references-and-borrowing.md)
    - [切片](ch04-03-slices.md)

- [使用结构体组织关联数据](ch05-00-structs.md)
    - [定义和实例化结构体](ch05-01-defining-structs.md)
    - [一个使用结构体的实例程序](ch05-02-example-structs.md)
    - [方法符号](ch05-03-method-syntax.md)

- [枚举和模式匹配](ch06-00-enums.md)
    - [枚举定义](ch06-01-defining-an-enum.md)
    - [`match` 流程控制](ch06-02-match.md)
    - [`if let` 表达式](ch06-03-if-let.md)

## Rust 扫盲

- [使用 `Packages`, `Crates`, `Modules` 组织项目](ch07-00-managing-growing-projects-with-packages-crates-and-modules.md)
    - [Packages 和 Crates](ch07-01-packages-and-crates.md)
    - [定义 Modules 控制 作用域 和 可见性](ch07-02-defining-modules-to-control-scope-and-privacy.md)
    - [模块树](ch07-03-paths-for-referring-to-an-item-in-the-module-tree.md)
    - [实用`use`引用模块](ch07-04-bringing-paths-into-scope-with-the-use-keyword.md)
    - [分割不同模块到不同的文件](ch07-05-separating-modules-into-different-files.md)

- [常用](ch08-00-common-collections.md)
    - [实用Vectors存储列表值](ch08-01-vectors.md)
    - [存储utf8字符串](ch08-02-strings.md)
    - [使用key访问hashmap内的值](ch08-03-hash-maps.md)

- [错误处理](ch09-00-error-handling.md)
    - [使用 `panic!` 处理无法恢复的错误](ch09-01-unrecoverable-errors-with-panic.md)
    - [使用 `Result` 处理可以恢复的错误](ch09-02-recoverable-errors-with-result.md)
    - [使用 `panic!` 还是不使用 `panic!`](ch09-03-to-panic-or-not-to-panic.md)

- [泛型, 特质, 生命周期](ch10-00-generics.md)
    - [泛型数据类型](ch10-01-syntax.md)
    - [特化: 定义共享行为](ch10-02-traits.md)
    - [实用生命周期验证引用](ch10-03-lifetime-syntax.md)

- [自动化测试](ch11-00-testing.md)
    - [如何编写测试](ch11-01-writing-tests.md)
    - [控制如何运行测试](ch11-02-running-tests.md)
    - [单元测试和集成测试](ch11-03-test-organization.md)

- [构建一个命令行程序](ch12-00-an-io-project.md)
    - [访问命令行参数](ch12-01-accepting-command-line-arguments.md)
    - [读取文件](ch12-02-reading-a-file.md)
    - [改善模块化和错误处理](ch12-03-improving-error-handling-and-modularity.md)
    - [TDD 编写测试](ch12-04-testing-the-librarys-functionality.md)
    - [环境变量](ch12-05-working-with-environment-variables.md)
    - [标准化错误输出](ch12-06-writing-to-stderr-instead-of-stdout.md)

## 用rust思考

- [迭代和闭包](ch13-00-functional-features.md)
    - [闭包: 闭包访问所属环境变量](ch13-01-closures.md)
    - [使用迭代顺序处理元素](ch13-02-iterators.md)
    - [完善命令行程序](ch13-03-improving-our-io-project.md)
    - [性能对比: Loops 对比 Iterators](ch13-04-performance.md)

- [智能指针](ch15-00-smart-pointers.md)
    - [使用 `Box<T>` 指向堆数据](ch15-01-box.md)
    - [`Deref` 特化](ch15-02-deref.md)
    - [`Drop` 特化](ch15-03-drop.md)
    - [`Rc<T>` 引用技术指针](ch15-04-rc.md)
    - [`RefCell<T>` 和  内部可变模式](ch15-05-interior-mutability.md)
    - [循环引用内存泄漏](ch15-06-reference-cycles.md)

- [并发](ch16-00-concurrency.md)
    - [实用线程同时执行代码](ch16-01-threads.md)
    - [线程之间消息传递](ch16-02-message-passing.md)
    - [并发共享状态](ch16-03-shared-state.md)
    - [`Sync` 和 `Send` 特化](ch16-04-extensible-concurrency-sync-and-send.md)

## 高级主题

- [模式和匹配](ch18-00-patterns.md)
    - [所有可以使用模式匹配的地方](ch18-01-all-the-places-for-patterns.md)
    - [反思: 是否有没有匹配到的模式](ch18-02-refutability.md)
    - [模式符号](ch18-03-pattern-syntax.md)

- [高级特效](ch19-00-advanced-features.md)
    - [`Unsafe` rust](ch19-01-unsafe-rust.md)
    - [高级 特化](ch19-03-advanced-traits.md)
    - [高级 类型](ch19-04-advanced-types.md)
    - [高级 函数和闭包](ch19-05-advanced-functions-and-closures.md)
    - [宏](ch19-06-macros.md)

- [终结项目: 构建一个多线程web服务器](ch20-00-final-project-a-web-server.md)
    - [构建一个单线程服务器](ch20-01-single-threaded.md)
    - [把单线程修改为多线程服务器](ch20-02-multithreaded.md)
    - [优雅退出](ch20-03-graceful-shutdown-and-cleanup.md)

- [附录](appendix-00.md)
    - [A - 关键字](appendix-01-keywords.md)
    - [B - 操作符和富豪](appendix-02-operators.md)
    - [C - 衍生特性](appendix-03-derivable-traits.md)
    - [D - 有用的开发工具](appendix-04-useful-development-tools.md)
    - [E - 版次](appendix-05-editions.md)
    - [F - 翻译本书](appendix-06-translation.md)
    - [G - 如何构建每日版本](appendix-07-nightly-rust.md)
