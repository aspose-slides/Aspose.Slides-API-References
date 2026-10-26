---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 将数据写入流。
type: docs
weight: 27
url: /zh/system.security.cryptography/cryptostream/write/
---
## CryptoStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


将数据写入流。

```cpp
void System::Security::Cryptography::CryptoStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 源数据缓冲区。 |
| offset | **int32_t** | 源缓冲区中的偏移量。 |
| count | **int32_t** | 要写入的字节数。 |

## CryptoStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法


将数据写入流。

```cpp
void System::Security::Cryptography::CryptoStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 源数据缓冲区。 |
| offset | **int32_t** | 源缓冲区中的偏移量。 |
| count | **int32_t** | 要写入的字节数。 |

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [CryptoStream](../)
* 命名空间 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)