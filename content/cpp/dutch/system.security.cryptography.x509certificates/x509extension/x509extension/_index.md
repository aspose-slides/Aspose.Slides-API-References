---
title: X509Extension()
second_title: Aspose.Slides voor C++ API-referentie
description: Constructor.
type: docs
weight: 1
url: /nl/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Geëncodeerde gegevens geassocieerd met certificaat. |
| critical | **bool** | Kritieke aanduiding. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) identificatie geassocieerd met extensie. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ruwe gegevens geassocieerd met certificaat. |
| critical | **bool** | Kritieke aanduiding. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identificatie geassocieerd met extensie. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ruwe gegevens geassocieerd met certificaat. |
| critical | **bool** | Kritieke aanduiding. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Klasse [X509Extension](../)
* Klasse [Oid](../../../system.security.cryptography/oid/)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Security::Cryptography::X509Certificates](../../)
* Bibliotheek [Aspose.Slides](../../../)