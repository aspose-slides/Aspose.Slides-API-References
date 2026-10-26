---
title: X509KeyUsageExtension()
second_title: Aspose.Slides für C++ API-Referenz
description: Standardkonstruktor.
type: docs
weight: 1
url: /de/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() constructor


Standardkonstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Kodierte Daten der Schlüsselverwendungen. |
| critical | **bool** | Kritikalitätszeichen. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) constructor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Schlüsselverwendungen. |
| critical | **bool** | Kritikalitätszeichen. |

## Siehe auch

* Aufzählung [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [X509KeyUsageExtension](../)
* Klasse [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Namensraum [System::Security::Cryptography::X509Certificates](../../)
* Bibliothek [Aspose.Slides](../../../)