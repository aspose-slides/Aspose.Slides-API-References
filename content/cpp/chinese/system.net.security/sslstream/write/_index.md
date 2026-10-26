---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的字节数组写入流。
type: docs
weight: 404
url: /zh/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) 方法

将指定的字节数组写入流。

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要写入的字节数组。 |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

将指定字节数组中指定的字节子范围写入流。

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要写入字节的数组 |
| offset | **int32_t** | 在 **buffer** 中子范围写入开始的元素的基于 0 的索引 |
| count | **int32_t** | 要写入的子范围中的元素数量 |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) 方法

将指定的字节数组写入流。

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 要写入的字节数组。 |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

将指定字节数组中指定的字节子范围写入流。

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要写入字节的数组 |
| offset | **int32_t** | 在 **buffer** 中子范围写入开始的元素的基于 0 的索引 |
| count | **int32_t** | 要写入的子范围中的元素数量 |

## 另见

* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类 [SslStream](../)
* 命名空间 [System::Net::Security](../../)
* 库 [Aspose.Slides](../../../)