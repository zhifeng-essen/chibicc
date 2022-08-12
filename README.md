# xcc

一个小型 C 编译器，参照 Rui Ueyama 的 [chibicc](https://github.com/rui314/chibicc) 实现。

[chibicc](https://github.com/rui314/chibicc) 项目是 Rui Ueyama 为自己的书 [《低レイヤを知りたい人のためのCコンパイラ作成入門》](https://www.sigbus.info/compilerbook) 写的参考实现。作者不仅对最终代码的可读性进行了把控，而是保证了每个 commit 的内容都相对独立，大小适中，且 commit log 写的非常清晰。读者可以随着 commit log 看到项目如何从只能输出一个整数的小程序，最终成长为一个可以完成自举的编译器。

## 过程记录（含部分原书翻译）

- [自制 C 编译器 - 00 - 搭建开发环境](https://www.zhifeng.games/posts/chibicc-compilerbook-step-00/)
- [自制 C 编译器 - 01 - 编译单个整数](https://www.zhifeng.games/posts/chibicc-compilerbook-step-01/)
- [自制 C 编译器 - 02 - 实现加减运算](https://www.zhifeng.games/posts/chibicc-compilerbook-step-02/)
- [自制 C 编译器 - 03 - 引入词法分析器](https://www.zhifeng.games/posts/chibicc-compilerbook-step-03/)
- [自制 C 编译器 - 04 - 改进错误信息](https://www.zhifeng.games/posts/chibicc-compilerbook-step-04/)
- [自制 C 编译器 - 05 - 实现四则运算](https://www.zhifeng.games/posts/chibicc-compilerbook-step-05/)
- [自制 C 编译器 - 06 - 实现一元加减运算](https://www.zhifeng.games/posts/chibicc-compilerbook-step-06/)
- [自制 C 编译器 - 07 - 加入比较运算符](https://www.zhifeng.games/posts/chibicc-compilerbook-step-07/)
