---
title: SignData()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的哈希算法计算指定数据数组的哈希值，并对结果进行签名。
type: docs
weight: 79
url: /zh/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

计算使用指定哈希算法的指定数据数组的哈希值，并对结果进行签名。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 输入数据数组。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。返回输入数据的 ECDSA 签名。 |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) 方法

计算使用指定哈希算法的指定数据数组的哈希值，并对结果进行签名。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 输入数据数组。 |
| offset | **int32_t** | 在 **data** 中的偏移量。 |
| count | **int32_t** | 用作输入数据的字节数。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。返回输入数据的 ECDSA 签名。 |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) 方法

计算使用指定哈希算法的二进制流的哈希值，并对结果进行签名。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 二进制流。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。返回输入数据的 ECDSA 签名。 |

## 另请参见

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* 类 [ECDsa](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* 命名空间 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)