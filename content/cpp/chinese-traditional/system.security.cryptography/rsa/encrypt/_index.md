---
title: Encrypt()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的填充模式加密輸入資料。
type: docs
weight: 53
url: /zh-hant/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) 方法

使用指定的填充模式加密輸入資料。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 要加密的陣列。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | 填充模式。 |

### 傳回值

加密後的資料，以位元組陣列格式。

## 另請參閱

* 型別定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [RSAEncryptionPadding](../../rsaencryptionpadding/)
* 類別 [RSA](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)