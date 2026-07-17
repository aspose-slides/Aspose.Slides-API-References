---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 参考
description: 验证指定哈希的签名是否有效。
type: docs
weight: 170
url: /zh/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) 方法

验证指定哈希的签名是否有效。

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 已签名数据的哈希值。 |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 签名数据。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | 填充模式。返回 true 如果签名有效，否则返回 false。 |

## 另见

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [RSASignaturePadding](../../rsasignaturepadding/)
* 类 [RSA](../)
* 结构体 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)