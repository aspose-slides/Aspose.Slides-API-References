---
title: GetCertContentType()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたバイト配列に含まれる証明書のタイプを取得します。
type: docs
weight: 391
url: /ja/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) メソッド

指定されたバイト配列に含まれる証明書のタイプを取得します。

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 証明書データ。 |

### 戻り値

X.509 証明書のタイプ。

## X509Certificate2::GetCertContentType(const String\&) メソッド

指定されたファイルに含まれる証明書のタイプを取得します。

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書ファイル名。 |

### 戻り値

X.509 証明書のタイプ。

## 参照

* 列挙型 [X509ContentType](../../x509contenttype/)
* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* クラス [X509Certificate2](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Security::Cryptography::X509Certificates](../../)
* ライブラリ [Aspose.Slides](../../../)