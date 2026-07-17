---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 将指定字节数组中指定子范围的字节写入流中。
type: docs
weight: 209
url: /zh/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

将指定字节数组中指定子范围的字节写入流中。

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要写入的字节的数组。 |
| offset | **int32_t** | 指定数组中字节的偏移量。 |
| size | **int32_t** | 要写入的子范围中元素的数量。 |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

将指定字节数组中指定子范围的字节写入流中。

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要写入字节的数组视图 |
| offset | **int32_t** | 写入子范围开始的元素在 **buffer** 中的 0 基索引 |
| size | **int32_t** | 要写入的子范围中元素的数量 |

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [NetworkStream](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)