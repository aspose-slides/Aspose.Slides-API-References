---
title: Peek()
second_title: Aspose.Slides for C++ API 参考
description: 从流中读取单个字符，而不更改流的读取光标。
type: docs
weight: 27
url: /zh/system.io/textreader/peek/
---
## TextReader::Peek() 方法


从流中读取单个字符，而不更改流的读取光标。

```cpp
virtual int System::IO::TextReader::Peek()
```

### 返回值

读取使用 UTF-16 编码的字符；如果读取的字符在 UTF-16 编码中由两个码点表示，则只返回高位代理对；如果未读取到字符，则返回 -1。

## 另见

* 类 [TextReader](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)