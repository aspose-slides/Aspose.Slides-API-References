---
title: X509KeyUsageExtension()
second_title: Aspose.Slides C++ API Referencia
description: Alapértelmezett konstruktor.
type: docs
weight: 1
url: /hu/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() konstruktor

Alapértelmezett konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | A kulcsfelhasználások kódolt adatai. |
| critical | **bool** | Kritikusság jelző. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Kulcsfelhasználások. |
| critical | **bool** | Kritikusság jelző. |

## Lásd még

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [X509KeyUsageExtension](../)
* Osztály [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Névterület [System::Security::Cryptography::X509Certificates](../../)
* Könyvtár [Aspose.Slides](../../../)