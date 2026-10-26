---
title: Read()
second_title: Aspose.Slides for C++ API 参考
description: 从流中读取数据。
type: docs
weight: 14
url: /zh/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

从流中读取数据。

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 目标数据缓冲区。 |
| offset | **int32_t** | 目标缓冲区的偏移。 |
| count | **int32_t** | 要读取的字节数。 |

### 返回值

实际读取的字节数。

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

从流中读取数据。

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 目标数据缓冲区。 |
| offset | **int32_t** | 目标缓冲区的偏移。 |
| count | **int32_t** | 要读取的字节数。 |

### 返回值

实际读取的字节数。

## 参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [CryptoStream](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)