---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 将指定字节数组中指定的字节子范围写入流。
type: docs
weight: 248
url: /zh/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

将指定字节数组中指定的字节子范围写入流。

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要写入的字节的数组。 |
| offset | **int32_t** | 在 **buffer** 中子范围写入开始位置的 0 基索引。 |
| count | **int32_t** | 要写入的子范围中的元素数量。 |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

将指定字节数组中指定的字节子范围写入流。

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要写入的字节的数组视图。 |
| offset | **int32_t** | 在 **buffer** 中子范围写入开始位置的 0 基索引。 |
| count | **int32_t** | 要写入的子范围中的元素数量。 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [FileStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)