---
title: Read()
second_title: Aspose.Slides C++ API 参考
description: 从流中读取单个字符。
type: docs
weight: 40
url: /zh/system.io/streamreader/read/
---
## StreamReader::Read() 方法

从流中读取单个字符。

```cpp
virtual int System::IO::StreamReader::Read() override
```

### 返回值

读取的字符使用 UTF-16 编码；如果读取的字符在 UTF-16 编码中由两个代码点表示，则仅返回高位代理项。

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) 方法

从流中读取指定数量的字符，将它们转换为 UTF-16 编码，并将生成的 UTF-16 字符写入指定的字符数组，从指定的位置开始写入。

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 用于写入从流中读取的字符的 UTF-16 字符数组 |
| index | int | 在 **buffer** 中的零基索引，指示写入的起始位置 |
| count | int | 从流中读取的字符数 |

### 返回值

从流中读取的字符数

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [StreamReader](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)