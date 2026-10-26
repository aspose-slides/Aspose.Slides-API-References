---
title: X509Extension()
second_title: Aspose.Slides pro C++ referenci API
description: Konstruktor.
type: docs
weight: 1
url: /cs/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Kódovaná data spojená s certifikátem. |
| critical | **bool** | Příznak kritičnosti. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | identifikátor [Object](../../../system/object/) spojený s rozšířením. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Surová data spojená s certifikátem. |
| critical | **bool** | Příznak kritičnosti. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | identifikátor [Object](../../../system/object/) spojený s rozšířením. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Surová data spojená s certifikátem. |
| critical | **bool** | Příznak kritičnosti. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Třída [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Třída [X509Extension](../)
* Třída [Oid](../../../system.security.cryptography/oid/)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Security::Cryptography::X509Certificates](../../)
* Knihovna [Aspose.Slides](../../../)