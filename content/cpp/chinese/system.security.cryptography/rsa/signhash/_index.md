---
title: SignHash()
second_title: Aspose.Slides C++ API 参考
description: 计算指定哈希值的签名。
type: docs
weight: 144
url: /zh/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) 方法

计算指定哈希值的签名。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 哈希值。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 哈希算法。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | 填充模式。返回 [RSA](../) 对指定哈希的签名。 |

## 另见

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [RSASignaturePadding](../../rsasignaturepadding/)
* 类 [RSA](../)
* 结构体 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)