---
title: Read()
second_title: Aspose.Slides C++ API 参考
description: 从流中读取单个字符。
type: docs
weight: 40
url: /zh/system.io/stringreader/read/
---
## StringReader::Read() 方法


从流中读取单个字符。

```cpp
virtual int System::IO::StringReader::Read() override
```


### 返回值

读取的字符，若未读取字符则返回 -1

## StringReader::Read(ArrayPtr\<char_t\>, int, int) 方法


从流中读取指定数量的字符到指定的字符数组，从指定位置开始。

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 用于写入从流中读取的字符的字符数组 |
| index | int | 在 **buffer** 中的基于0的索引，指示写入开始的位置 |
| count | int | 要从流中读取的字符数量 |

### 返回值

从流中读取的字符数量

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [StringReader](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)