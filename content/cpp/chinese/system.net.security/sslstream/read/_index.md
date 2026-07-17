---
title: Read()
second_title: Aspose.Slides for C++ API 参考文档
description: 从流中读取指定数量的字节并写入到指定的字节数组。
type: docs
weight: 391
url: /zh/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

从流中读取指定数量的字节并写入到指定的字节数组。

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用于写入读取字节的字节数组 |
| offset | **int32_t** | 在 **buffer** 中的0基起始位置 |
| count | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

从流中读取指定数量的字节并写入到指定的字节数组。

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用于写入读取字节的字节数组 |
| offset | **int32_t** | 在 **buffer** 中的0基起始位置 |
| count | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [SslStream](../)
* 命名空间 [System::Net::Security](../../)
* 库 [Aspose.Slides](../../../)