---
title: GetCertContentType()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het type certificaat op dat in de opgegeven byte array staat.
type: docs
weight: 391
url: /nl/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) methode

Haalt het type certificaat op dat in de opgegeven byte array staat.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Certificate data. |

### Retourwaarde

Type X.509-certificaat.

## X509Certificate2::GetCertContentType(const String\&) methode

Haalt het type certificaat op dat in het opgegeven bestand staat.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Certificate file name. |

### Retourwaarde

Type X.509-certificaat.

## Zie ook

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [X509Certificate2](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)