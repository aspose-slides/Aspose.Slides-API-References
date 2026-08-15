---
title: SignHash()
second_title: Aspose.Slides for C++ API 參考
description: 計算指定雜湊值的簽章。
type: docs
weight: 196
url: /zh-hant/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) method

計算指定雜湊值的簽章。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 雜湊值。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 雜湊演算法。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | 填充模式。返回 [RSA](../../rsa/) 簽章以供指定的雜湊。 |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) method

計算指定輸入值的簽章。未實作。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 要簽名的資料之雜湊值。 |
| str | const [String](../../../system/string/)\& | 用於產生雜湊的雜湊演算法識別碼。 |

### 返回值

[RSA](../../rsa/) 簽章供指定資料。

## 另請參閱

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [RSASignaturePadding](../../rsasignaturepadding/)
* 類別 [RSACryptoServiceProvider](../)
* 類別 [String](../../../system/string/)
* 結構 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)