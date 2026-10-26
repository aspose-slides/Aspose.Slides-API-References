---
title: Read()
second_title: Aspose.Slides for C++ API 参考
description: 从流中读取指定数量的字节并将其写入指定的字节数组。
type: docs
weight: 27
url: /zh/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

从流中读取指定数量的字节并将其写入指定的字节数组。

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用于写入读取字节的字节数组 |
| offset | **int32_t** | 在 **buffer** 中的基于 0 的起始写入位置 |
| count | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

从流中读取指定数量的字节并将其写入指定的字节数组。

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用于写入读取字节的字节数组视图 |
| offset | **int32_t** | 在 **buffer** 中的基于 0 的起始写入位置 |
| count | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) 方法

从流中读取指定数量的字节并将其写入指定的字节数组。

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| N | 堆栈数组的大小 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | 用于写入读取字节的字节堆栈数组 |
| offset | **int32_t** | 在 **buffer** 中的基于 0 的起始写入位置 |
| count | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## Stream::Read(const System::Span\<uint8_t\>\&) 方法

从流中读取指定数量的字节并将其写入指定的字节跨度。

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | 用于写入读取字节的字节跨度 |

### 返回值

读取的字节数

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Stream](../)
* 类 [Span](../../../system/span/)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)