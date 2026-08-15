---
title: SignHash()
second_title: Aspose.Slides for C++ API 參考
description: 計算指定雜湊值的簽章。
type: docs
weight: 144
url: /zh-hant/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) 方法

計算指定的雜湊值的簽章。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 雜湊值。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 雜湊演算法。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | 填充模式。回傳 [RSA](../) 簽章，針對指定的雜湊值。 |

## 相關參考

* 型別定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [RSASignaturePadding](../../rsasignaturepadding/)
* 類別 [RSA](../)
* 結構 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)