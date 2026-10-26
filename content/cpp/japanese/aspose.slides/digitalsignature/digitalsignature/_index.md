---
title: DigitalSignature()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された証明書で新しい DigitalSignature オブジェクトを作成します。
type: docs
weight: 66
url: /ja/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) コンストラクタ

指定された証明書を使用して新しい[DigitalSignature](../)オブジェクトを作成します。

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | プレゼンテーションに署名するために使用される証明書。 |

## DigitalSignature::DigitalSignature(System::String, System::String) コンストラクタ

指定された証明書ファイルパスとパスワードを使用して新しい[DigitalSignature](../)オブジェクトを作成します。

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | 証明書が含まれるファイルへのパス。 |
| password | [System::String](../../../system/string/) | 証明書にアクセスするために必要なパスワード。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* クラス [DigitalSignature](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)