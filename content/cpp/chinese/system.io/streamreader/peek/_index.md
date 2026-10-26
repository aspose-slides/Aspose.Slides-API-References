---
title: Peek()
second_title: Aspose.Slides for C++ API 参考
description: 读取流中的单个字符，但不更改流的读取指针。
type: docs
weight: 27
url: /zh/system.io/streamreader/peek/
---
## StreamReader::Peek() 方法

读取流中的单个字符，但不更改流的读取指针。

```cpp
virtual int System::IO::StreamReader::Peek() override
```

### 返回值

读取的字符使用 UTF-16 编码；如果读取的字符在 UTF-16 编码中由两个码点表示，则只返回高位代理项；如果未读取到字符，则返回 -1。

## 另见

* 类 [StreamReader](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)