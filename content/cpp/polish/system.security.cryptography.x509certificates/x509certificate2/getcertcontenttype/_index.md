---
title: GetCertContentType()
second_title: Aspose.Slides dla C++ - Referencja API
description: Pobiera typ certyfikatu zawartego w określonej tablicy bajtów.
type: docs
weight: 391
url: /pl/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) metoda


Pobiera typ certyfikatu zawartego w określonej tablicy bajtów.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dane certyfikatu. |

### Wartość zwracana

Typ certyfikatu X.509.

## X509Certificate2::GetCertContentType(const String\&) metoda


Pobiera typ certyfikatu zawartego w określonym pliku.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nazwa pliku certyfikatu. |

### Wartość zwracana

Typ certyfikatu X.509.

## Zobacz także

* Wyliczenie [X509ContentType](../../x509contenttype/)
* Definicja typu [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasa [X509Certificate2](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Security::Cryptography::X509Certificates](../../)
* Biblioteka [Aspose.Slides](../../../)