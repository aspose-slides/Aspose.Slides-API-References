---
title: Decrypt()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的填充模式解密輸入資料。
type: docs
weight: 27
url: /zh-hant/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) 方法

使用指定的填充模式解密輸入資料。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 陣列以供解密。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | 填充模式。 |

### 回傳值

以位元組陣列格式返回的已解密資料。

## 另見

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)