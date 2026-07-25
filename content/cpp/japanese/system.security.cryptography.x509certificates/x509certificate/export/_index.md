---
title: Export()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された形式を使用して、現在のオブジェクトをバイト配列にエクスポートします。実装されていません。
type: docs
weight: 287
url: /ja/system.security.cryptography.x509certificates/x509certificate/export/
---
## X509Certificate::Export(X509ContentType) const メソッド

指定された形式を使用して、現在のオブジェクトをバイト配列にエクスポートします。実装されていません。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | 出力データの形式を指定します。 |

### 戻り値

現在のオブジェクトを表すバイト配列です。

## X509Certificate::Export(X509ContentType, const SecureStringPtr\&) const メソッド

指定された形式を使用して、現在のオブジェクトをバイト配列にエクスポートします。実装されていません。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const SecureStringPtr &password) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | 出力データの形式を指定します。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 証明書データにアクセスするために必要なパスワードです。 |

### 戻り値

現在のオブジェクトを表すバイト配列です。

## X509Certificate::Export(X509ContentType, const String\&) const メソッド

指定された形式を使用して、現在のオブジェクトをバイト配列にエクスポートします。実装されていません。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const String &password) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | 出力データの形式を指定します。 |
| password | const [String](../../../system/string/)\& | 証明書データにアクセスするために必要なパスワードです。 |

### 戻り値

現在のオブジェクトを表すバイト配列です。

## 参照

* 列挙体 [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* クラス [X509Certificate](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)