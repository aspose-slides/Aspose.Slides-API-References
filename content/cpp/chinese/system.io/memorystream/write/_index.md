---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 将指定字节数组中的指定子范围字节写入流中。
type: docs
weight: 92
url: /zh/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

将指定字节数组中的指定子范围字节写入流中。

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要写入的字节的数组 |
| offset | **int32_t** | **buffer** 中子范围写入开始的基于0的索引 |
| count | **int32_t** | 要写入的子范围中的元素数量 |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

将指定字节数组中的指定子范围字节写入流中。

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要写入字节的数组视图 |
| offset | **int32_t** | **buffer** 中子范围写入开始的基于0的索引 |
| count | **int32_t** | 要写入的子范围中的元素数量 |

## 另请参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [MemoryStream](../)
* 命名空间 [System::IO](../../)
* Library [Aspose.Slides](../../../)