---
title: GetCertContentType()
second_title: Aspose.Slides for C++ API-referencia
description: Lekéri a megadott bájt tömbben található tanúsítvány típusát.
type: docs
weight: 391
url: /hu/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) method

Lekéri a megadott bájt tömbben található tanúsítvány típusát.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tanúsítvány adat. |

### Visszatérési érték

X.509 tanúsítvány típusa.

## X509Certificate2::GetCertContentType(const String\&) method

Lekéri a megadott fájlban található tanúsítvány típusát.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Tanúsítvány fájl neve. |

### Visszatérési érték

X.509 tanúsítvány típusa.

## Lásd még

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)