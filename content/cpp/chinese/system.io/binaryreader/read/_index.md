---
title: Read()
second_title: Aspose.Slides for C++ API 参考
description: 从输入流读取单个字符。
type: docs
weight: 66
url: /zh/system.io/binaryreader/read/
---
## BinaryReader::Read() 方法

读取输入流中的单个字符。

```cpp
virtual int System::IO::BinaryReader::Read()
```

### 返回值

读取使用 UTF-16 编码的字符；如果读取的字符在 UTF-16 编码中由两个代码点表示，则仅返回高位代理。

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) 方法

从输入流读取指定数量的字节并将其写入指定的字节数组。

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 写入读取字节的字节数组 |
| index | int | 在 **buffer** 中以 0 为基准的写入起始位置 |
| count | int | 要读取的字节数 |

### 返回值

读取的字节数

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) 方法

从输入流读取指定数量的字符，转换为 UTF-16 编码，并将生成的 UTF-16 字符写入指定字符数组的指定位置。

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 写入从输入流读取的字符的 UTF-16 字符数组 |
| index | int | 在 **buffer** 中以 0 为基准的写入起始索引 |
| count | int | 从流中读取的字符数 |

### 返回值

从输入流读取的字符数

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [BinaryReader](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)