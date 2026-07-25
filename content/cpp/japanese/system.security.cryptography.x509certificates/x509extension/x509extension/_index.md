---
title: X509Extension()
second_title: Aspose.Slides for C++ API リファレンス
description: コンストラクタ。
type: docs
weight: 1
url: /ja/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | 証明書に関連付けられたエンコードデータ。 |
| critical | **bool** | クリティカル性サイン。 |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) 識別子が拡張に関連付けられます。 |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 証明書に関連付けられた生データ。 |
| critical | **bool** | クリティカル性サイン。 |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) 識別子が拡張に関連付けられます。 |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 証明書に関連付けられた生データ。 |
| critical | **bool** | クリティカル性サイン。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* クラス [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* クラス [X509Extension](../)
* クラス [Oid](../../../system.security.cryptography/oid/)
* クラス [String](../../../system/string/)
* 名前空間 [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)