---
title: PublicKey()
second_title: Aspose.Slides for C++ API リファレンス
description: コンストラクタ。
type: docs
weight: 1
url: /ja/system.security.cryptography.x509certificates/publickey/publickey/
---
## PublicKey::PublicKey(const SharedPtr\<Oid\>\&, const SharedPtr\<AsnEncodedData\>\&, const SharedPtr\<AsnEncodedData\>) constructor


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::PublicKey::PublicKey(const SharedPtr<Oid> &oid, const SharedPtr<AsnEncodedData> &parameters, const SharedPtr<AsnEncodedData> key_value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | 公開鍵を表す識別子オブジェクト。 |
| parameters | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | ASN.1 エンコードされた公開鍵パラメータ。 |
| key_value | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\> | ASN.1 エンコードされた公開鍵の値。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Oid](../../../system.security.cryptography/oid/)
* クラス [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* クラス [PublicKey](../)
* 名前空間 [System::Security::Cryptography::X509Certificates](../../)
* ライブラリ [Aspose.Slides](../../../)