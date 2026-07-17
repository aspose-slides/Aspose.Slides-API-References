---
title: ReadBlock()
second_title: Aspose.Slides for C++ API 参考
description: 从当前文本读取器读取指定的最大字符数，并将数据写入缓冲区，从指定的索引开始。
type: docs
weight: 53
url: /zh/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) method


从当前文本读取器读取指定的最大字符数，并将数据写入缓冲区，从指定的索引开始。

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 用于写入读取数据的字符缓冲区 |
| index | int | **buffer** 中的 0 基索引，指示写入起始位置 |
| count | int | 要读取的最大字符数 |

### 返回值

实际读取的字符数

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [TextReader](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)