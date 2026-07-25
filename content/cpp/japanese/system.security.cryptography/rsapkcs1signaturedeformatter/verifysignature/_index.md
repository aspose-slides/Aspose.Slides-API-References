---
title: VerifySignature()
second_title: Aspose.Slides for C++ APIリファレンス
description: データハッシュの署名を検証します。
type: docs
weight: 40
url: /ja/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) メソッド


データハッシュの署名を検証します。

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | データに対して計算されたハッシュ。 |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | データに対して受信した署名。 |

### 戻り値

True が有効で、false は無効です。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RSAPKCS1SignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)