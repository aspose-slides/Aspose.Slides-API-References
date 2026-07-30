---
title: GetCertContentType()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá typ certifikátu obsaženého ve specifikovaném poli bajtů.
type: docs
weight: 391
url: /cs/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) metoda

Získá typ certifikátu obsaženého ve specifikovaném poli bajtů.
```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data certifikátu. |

### Návratová hodnota

Typ X.509 certifikátu.

## X509Certificate2::GetCertContentType(const String\&) metoda

Získá typ certifikátu obsaženého ve specifikovaném souboru.
```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Název souboru certifikátu. |

### Návratová hodnota

Typ X.509 certifikátu.

## Viz také

* Výčtový typ [X509ContentType](../../x509contenttype/)
* Definice typu [ByteArrayPtr](../../../system/bytearrayptr/)
* Třída [X509Certificate2](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Security::Cryptography::X509Certificates](../../)
* Knihovna [Aspose.Slides](../../../)