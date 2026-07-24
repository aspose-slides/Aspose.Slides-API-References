---
title: GetCertContentType()
second_title: Aspose.Slides für C++ API Referenz
description: Ermittelt den Typ des Zertifikats, das im angegebenen Byte-Array enthalten ist.
type: docs
weight: 391
url: /de/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) Methode

Ermittelt den Typ des Zertifikats, das im angegebenen Byte-Array enthalten ist.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Zertifikatsdaten. |

### Rückgabewert

Typ des X.509-Zertifikats.

## X509Certificate2::GetCertContentType(const String\&) Methode

Ermittelt den Typ des Zertifikats, das in der angegebenen Datei enthalten ist.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Dateiname des Zertifikats. |

### Rückgabewert

Typ des X.509-Zertifikats.

## Siehe auch

* Aufzählung [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [X509Certificate2](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Security::Cryptography::X509Certificates](../../)
* Bibliothek [Aspose.Slides](../../../)