---
title: Read()
second_title: Aspose.Slides for C++ API 参考
description: 从流中读取指定数量的字节并将其写入指定的字节数组。
type: docs
weight: 144
url: /zh/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

从流中读取指定数量的字节并将其写入指定的字节数组。

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用于写入读取字节的字节数组 |
| offset | **int32_t** | **buffer** 中的基于 0 的写入起始位置 |
| count | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

从流中读取指定数量的字节并将其写入指定的字节数组。

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用于写入读取字节的字节数组视图 |
| offset | **int32_t** | **buffer** 中的基于 0 的写入起始位置 |
| count | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [UnmanagedMemoryStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)