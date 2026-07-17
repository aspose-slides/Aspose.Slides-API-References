---
title: Encrypt()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的填充模式加密输入数据。
type: docs
weight: 53
url: /zh/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


使用指定的填充模式加密输入数据。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 用于加密的数组。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | 填充模式。 |

### 返回值

加密后以字节数组格式的结果。

## 另见

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [RSAEncryptionPadding](../../rsaencryptionpadding/)
* 类 [RSA](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)