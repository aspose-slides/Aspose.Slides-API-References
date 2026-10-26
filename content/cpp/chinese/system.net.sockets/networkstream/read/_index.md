---
title: Read()
second_title: Aspose.Slides C++ API 参考
description: 从流中读取指定数量的字节并将其写入指定的字节数组。
type: docs
weight: 196
url: /zh/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

从流中读取指定数量的字节，并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 读取的字节将被写入的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要读取的字节数。 |

### 返回值

读取的字节数。

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

从流中读取指定数量的字节，并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 要写入读取字节的字节数组视图 |
| offset | **int32_t** | 在 **buffer** 中开始写入的 0 基位置 |
| size | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [NetworkStream](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)