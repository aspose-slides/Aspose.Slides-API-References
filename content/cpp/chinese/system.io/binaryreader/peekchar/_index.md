---
title: PeekChar()
second_title: Aspose.Slides for C++ API 参考
description: 从输入流读取单个字符，但不更改流的读取光标。
type: docs
weight: 53
url: /zh/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() method

读取输入流中的单个字符，但不更改流的读取光标。

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```

### 返回值

读取的字符使用 UTF-16 编码；如果读取的字符在 UTF-16 编码中由两个代码点表示，则仅返回高位代理项；如果未读取到字符，则返回 -1

## 另见

* 类 [BinaryReader](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)