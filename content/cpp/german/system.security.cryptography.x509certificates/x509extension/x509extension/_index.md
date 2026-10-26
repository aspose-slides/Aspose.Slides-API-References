---
title: X509Extension()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruktor.
type: docs
weight: 1
url: /de/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Kodierte Daten, die dem Zertifikat zugeordnet sind. |
| critical | **bool** | Kritikalitätskennzeichen. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) Bezeichner, der mit der Erweiterung verknüpft ist. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Rohdaten, die dem Zertifikat zugeordnet sind. |
| critical | **bool** | Kritikalitätskennzeichen. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) Bezeichner, der mit der Erweiterung verknüpft ist. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Rohdaten, die dem Zertifikat zugeordnet sind. |
| critical | **bool** | Kritikalitätskennzeichen. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Klasse [X509Extension](../)
* Klasse [Oid](../../../system.security.cryptography/oid/)
* Klasse [String](../../../system/string/)
* Namensraum [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)