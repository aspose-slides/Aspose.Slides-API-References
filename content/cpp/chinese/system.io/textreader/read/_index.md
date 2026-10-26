---
title: Read()
second_title: Aspose.Slides C++ API 参考
description: 从流中读取单个字符。
type: docs
weight: 40
url: /zh/system.io/textreader/read/
---
## TextReader::Read() 方法

从流中读取单个字符。

```cpp
virtual int System::IO::TextReader::Read()
```

### 返回值

读取的字符采用 UTF-16 编码；如果读取的字符在 UTF-16 编码中由两个代码单元表示，则仅返回高位代理项。

## TextReader::Read(ArrayPtr\<char_t\>, int, int) 方法

从流中读取指定数量的字符，并将它们写入指定字符数组的指定位置。

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 用于写入从流中读取的字符的 UTF-16 字符数组 |
| index | int | **buffer** 中的 0 基索引，表示写入的起始位置 |
| count | int | 要从流中读取的字符数 |

### 返回值

从流中读取的字符数

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [TextReader](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)