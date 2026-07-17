---
title: Read()
second_title: Aspose.Slides for C++ API 参考
description: 从流中读取指定字节数，并将其写入指定的字节数组。
type: docs
weight: 79
url: /zh/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


从流中读取指定字节数，并将其写入指定的字节数组。

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用于写入读取字节的字节数组 |
| offset | **int32_t** | 在 **buffer** 中开始写入的基于0的位置 |
| count | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法


从流中读取指定字节数，并将其写入指定的字节数组。

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用于写入读取字节的字节数组视图 |
| offset | **int32_t** | 在 **buffer** 中开始写入的基于0的位置 |
| count | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [MemoryStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)