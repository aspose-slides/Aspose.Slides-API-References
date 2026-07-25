---
title: GetNameInfo()
second_title: Aspose.Slides for C++ API リファレンス
description: 証明書からサブジェクトまたは発行者の名前を取得します。
type: docs
weight: 248
url: /ja/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const メソッド

証明書からサブジェクトまたは発行者の名前を取得します。

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | 名前の書式設定オプション。 |
| for_issuer | **bool** | true の場合は発行者名を返し、false の場合はサブジェクト名を返します。 |

### 戻り値

書式設定された発行者名またはサブジェクト名。

## 参照

* 列挙体 [X509NameType](../../x509nametype/)
* クラス [String](../../../system/string/)
* クラス [X509Certificate2](../)
* 名前空間 [System::Security::Cryptography::X509Certificates](../../)
* ライブラリ [Aspose.Slides](../../../)