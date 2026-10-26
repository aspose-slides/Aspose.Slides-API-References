---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 将指定字节数组中指定的字节子范围写入流。
type: docs
weight: 53
url: /zh/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

将指定字节数组中指定的字节子范围写入流。

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要写入的字节的数组 |
| offset | **int32_t** | **buffer** 中子范围写入起始位置的基于 0 的索引 |
| count | **int32_t** | 要写入的子范围中元素的数量 |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

将指定字节数组中指定的字节子范围写入流。

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要写入的字节的数组视图 |
| offset | **int32_t** | **buffer** 中子范围写入起始位置的基于 0 的索引 |
| count | **int32_t** | 要写入的子范围中元素的数量 |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method

将指定字节数组中指定的字节子范围写入流。

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| N | 堆栈数组的大小 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | 包含要写入的字节的堆栈数组 |
| offset | **int32_t** | **buffer** 中子范围写入起始位置的基于 0 的索引 |
| count | **int32_t** | 要写入的子范围中元素的数量 |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) method

将指定字节跨度中指定的字节子范围写入流。

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | 要读取已写入字节的字节跨度 |

## 参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Stream](../)
* 类 [ReadOnlySpan](../../../system/readonlyspan/)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)