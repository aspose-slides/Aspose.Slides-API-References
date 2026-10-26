---
title: X509KeyUsageExtension()
second_title: Aspose.Slides för C++ API-referens
description: Standardkonstruktor.
type: docs
weight: 1
url: /sv/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() konstruktor

Standardkonstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Kodade data för nyckelanvändningar. |
| critical | **bool** | Kritikalitetstecken. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Nyckelanvändningar. |
| critical | **bool** | Kritikalitetstecken. |

## Se även

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [X509KeyUsageExtension](../)
* Klass [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Namnrymd [System::Security::Cryptography::X509Certificates](../../)
* Bibliotek [Aspose.Slides](../../../)