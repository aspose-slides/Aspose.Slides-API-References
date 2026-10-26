---
title: Decrypt()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的填充模式解密输入数据。
type: docs
weight: 27
url: /zh/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) 方法

使用指定的填充模式解密输入数据。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 要解密的数组。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | 填充模式。 |

### 返回值

以字节数组格式的解密数据。

## 另请参阅

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [RSAEncryptionPadding](../../rsaencryptionpadding/)
* 类 [RSA](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)