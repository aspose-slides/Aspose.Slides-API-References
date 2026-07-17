---
title: SignHash()
second_title: Aspose.Slides C++ API 参考
description: 计算指定哈希值的签名。
type: docs
weight: 196
url: /zh/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) 方法

计算指定哈希值的签名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 哈希值。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 哈希算法。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | 填充模式。返回 [RSA](../../rsa/) 指定哈希的签名。 |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) 方法

计算指定输入值的签名。未实现。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 要签名的数据的哈希值。 |
| str | const [String](../../../system/string/)\& | 用于创建哈希的哈希算法标识符。 |

### 返回值

[RSA](../../rsa/) 指定数据的签名。

## 另见

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)