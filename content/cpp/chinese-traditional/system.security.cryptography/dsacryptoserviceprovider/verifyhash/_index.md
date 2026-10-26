---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查資料簽章。
type: docs
weight: 222
url: /zh-hant/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) 方法


檢查資料簽章。

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash calculated for received data. |
| str | const [String](../../../system/string/)\& | Name of hash algorithm used. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature as received. |

### 返回值

若簽章有效則返回 true，否則返回 false。

## 另請參見

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [DSACryptoServiceProvider](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)