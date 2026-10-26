---
title: X500DistinguishedName()
second_title: Aspose.Slides for C++ API リファレンス
description: コンストラクタ。
type: docs
weight: 1
url: /ja/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) constructor


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) を表す識別名。 |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) constructor


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた識別名。 |

## X500DistinguishedName::X500DistinguishedName(const String\&) constructor


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | 識別名。 |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) constructor


コピーコンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | データをコピーする識別名。 |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) constructor


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | 識別名。 |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | 名前構築プロパティを指定するビット単位で組み合わせたフラグ。 |

## 参照

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X500DistinguishedName](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)