---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 參考
description: 檢查資料簽章。
type: docs
weight: 222
url: /zh-hant/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) 方法

檢查資料簽章。

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 為接收資料計算的雜湊。 |
| str | const [String](../../../system/string/)\& | 使用的雜湊演算法名稱。 |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 接收的簽章。 |

### 返回值

如果簽章有效則返回 True，否則返回 false。

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) 方法

驗證指定雜湊的簽章是否有效。

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 已簽名資料的雜湊值。 |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | 填充模式。若簽章有效則返回 true，否則返回 false。 |

## 參見

* 類型別名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [RSACryptoServiceProvider](../)
* 類別 [RSASignaturePadding](../../rsasignaturepadding/)
* 結構 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)