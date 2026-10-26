---
title: SignData()
second_title: Aspose.Slides C++ API 参考
description: 计算指定数据数组的哈希值，并对结果进行签名。
type: docs
weight: 131
url: /zh/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) 方法

计算指定数据数组的哈希值，并对结果进行签名。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 输入数据数组。返回 ECDSA 签名用于输入数据。 |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) 方法

计算指定数据数组的哈希值，并对结果进行签名。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 输入数据数组。 |
| offset | **int32_t** | **data** 中的偏移。 |
| count | **int32_t** | 作为输入数据使用的字节数。返回 ECDSA 签名用于输入数据。 |

## ECDsaBotan::SignData(const StreamPtr\&) 方法

计算指定二进制流的哈希值，并对结果进行签名。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 二进制流。返回 ECDSA 签名用于输入数据。 |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

使用指定的哈希算法计算指定数据数组的哈希值，并对结果进行签名。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 输入数据数组。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。返回 ECDSA 签名用于输入数据。 |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) 方法

使用指定的哈希算法计算指定数据数组的哈希值，并对结果进行签名。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 输入数据数组。 |
| offset | **int32_t** | **data** 中的偏移。 |
| count | **int32_t** | 作为输入数据使用的字节数。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。返回 ECDSA 签名用于输入数据。 |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) 方法

使用指定的哈希算法计算指定二进制流的哈希值，并对结果进行签名。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 二进制流。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。返回 ECDSA 签名用于输入数据。 |

## 另请参阅

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)