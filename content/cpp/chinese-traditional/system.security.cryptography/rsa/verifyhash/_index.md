---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 參考
description: 驗證指定雜湊的簽章是否有效。
type: docs
weight: 170
url: /zh-hant/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) method

驗證指定雜湊的簽章是否有效。

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 已簽名資料的雜湊值。 |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | 填充模式。若簽章有效則返回 true，否則返回 false。 |

## 另請參閱

* 類型別名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [RSASignaturePadding](../../rsasignaturepadding/)
* 類別 [RSA](../)
* 結構 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)