---
title: SignData()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的哈希算法和填充方式计算指定数据数组的哈希值，并对结果进行签名。
type: docs
weight: 131
url: /zh/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 方法

使用指定的哈希算法和填充方式计算指定数据数组的哈希值，并对结果进行签名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 输入数据数组。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 填充模式。返回 [RSA](../) 签名用于输入数据。 |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 方法

使用指定的哈希算法和填充方式计算指定数据数组的哈希值，并对结果进行签名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 输入数据数组。 |
| offset | **int32_t** | **data** 中的偏移量。 |
| count | **int32_t** | 用作输入数据的字节数。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 填充模式。返回 [RSA](../) 签名用于输入数据。 |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 方法

使用指定的哈希算法和填充方式计算指定二进制流的哈希值，并对结果进行签名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 二进制流。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 填充模式。返回 [RSA](../) 签名用于输入数据。 |

## 另请参阅

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [StreamPtr](../../../system/streamptr/)
* 类 [RSASignaturePadding](../../rsasignaturepadding/)
* 类 [RSA](../)
* 结构体 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)