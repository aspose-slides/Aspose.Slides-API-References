---
title: X500DistinguishedName()
second_title: Aspose.Slides for C++ API 參考
description: 建構函式。
type: docs
weight: 1
url: /zh-hant/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) 表示識別名稱。 |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已編碼的識別名稱。 |

## X500DistinguishedName::X500DistinguishedName(const String\&) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | 識別名稱。 |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) 複製建構函式


複製建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | 要從中複製資料的識別名稱。 |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | 識別名稱。 |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | 位元組組合的旗標，指定名稱建構屬性。 |

## 參見

* 列舉 [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類別 [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* 類別 [X500DistinguishedName](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Security::Cryptography::X509Certificates](../../)
* 函式庫 [Aspose.Slides](../../../)