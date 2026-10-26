---
title: X509KeyUsageExtension()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konstruktor domyślny.
type: docs
weight: 1
url: /pl/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() konstruktor

Konstruktor domyślny.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Zakodowane dane użycia klucza. |
| critical | **bool** | Znak krytyczności. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Użycia klucza. |
| critical | **bool** | Znak krytyczności. |

## Zobacz także

* Wyliczenie [X509KeyUsageFlags](../../x509keyusageflags/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [X509KeyUsageExtension](../)
* Klasa [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Przestrzeń nazw [System::Security::Cryptography::X509Certificates](../../)
* Biblioteka [Aspose.Slides](../../../)