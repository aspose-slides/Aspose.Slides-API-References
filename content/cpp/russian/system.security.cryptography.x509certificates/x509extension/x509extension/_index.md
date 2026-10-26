---
title: X509Extension()
second_title: Справочник API Aspose.Slides для C++
description: Конструктор.
type: docs
weight: 1
url: /ru/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Закодированные данные, связанные с сертификатом. |
| critical | **bool** | Признак критичности. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) идентификатор, связанный с расширением. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Необработанные данные, связанные с сертификатом. |
| critical | **bool** | Признак критичности. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) идентификатор, связанный с расширением. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Необработанные данные, связанные с сертификатом. |
| critical | **bool** | Признак критичности. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X509Extension](../)
* Class [Oid](../../../system.security.cryptography/oid/)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)