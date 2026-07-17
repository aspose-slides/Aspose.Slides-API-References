---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 参考
description: 检查数据签名。
type: docs
weight: 222
url: /zh/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr&, const String&, const ByteArrayPtr&) 方法

检查数据签名。

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)& | 对接收的数据计算的哈希。 |
| str | const [String](../../../system/string/)& | 使用的哈希算法名称。 |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)& | 接收到的签名。 |

### 返回值

如果签名有效则返回 true，否则返回 false。

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName&, SharedPtr<RSASignaturePadding>) 方法

验证指定哈希的签名是否有效。

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 签名数据的哈希值。 |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 签名数据。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)& | 哈希算法。 |
| padding | [SharedPtr](../../../system/sharedptr/)<[RSASignaturePadding](../../rsasignaturepadding/)> | 填充模式。返回 true 如果签名有效，否则返回 false。 |

## 参见

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)