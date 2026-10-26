---
title: X509Extension()
second_title: Aspose.Slides for C++ API 參考文件
description: 建構函式。
type: docs
weight: 1
url: /zh-hant/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | 與憑證相關的編碼資料。 |
| critical | **bool** | 關鍵性標誌。 |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) 識別碼與擴充功能相關。 |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 與憑證相關的原始資料。 |
| critical | **bool** | 關鍵性標誌。 |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) 識別碼與擴充功能相關。 |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 與憑證相關的原始資料。 |
| critical | **bool** | 關鍵性標誌。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* 類別 [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* 類別 [X509Extension](../)
* 類別 [Oid](../../../system.security.cryptography/oid/)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)