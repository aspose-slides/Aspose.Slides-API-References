---
title: PublicKey()
second_title: Aspose.Slides for C++ API 參考
description: 建構函式。
type: docs
weight: 1
url: /zh-hant/system.security.cryptography.x509certificates/publickey/publickey/
---
## PublicKey::PublicKey(const SharedPtr\<Oid\>\&, const SharedPtr\<AsnEncodedData\>\&, const SharedPtr\<AsnEncodedData\>) 建構函式

建構函式。

```cpp
System::Security::Cryptography::X509Certificates::PublicKey::PublicKey(const SharedPtr<Oid> &oid, const SharedPtr<AsnEncodedData> &parameters, const SharedPtr<AsnEncodedData> key_value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | 表示公開金鑰的識別碼物件。 |
| parameters | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | ASN.1 編碼的公開金鑰參數。 |
| key_value | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\> | ASN.1 編碼的公開金鑰值。 |

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Oid](../../../system.security.cryptography/oid/)
* 類別 [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* 類別 [PublicKey](../)
* 命名空間 [System::Security::Cryptography::X509Certificates](../../)
* 函式庫 [Aspose.Slides](../../../)