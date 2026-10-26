---
title: X509KeyUsageExtension()
second_title: Aspose.Slides pro C++ – reference API
description: Výchozí konstruktor.
type: docs
weight: 1
url: /cs/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() konstruktor

Výchozí konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Kódovaná data použití klíčů. |
| critical | **bool** | Znak kritičnosti. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Použití klíčů. |
| critical | **bool** | Znak kritičnosti. |

## Viz také

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [X509KeyUsageExtension](../)
* Třída [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Jmenný prostor [System::Security::Cryptography::X509Certificates](../../)
* Knihovna [Aspose.Slides](../../../)