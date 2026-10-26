---
title: X509KeyUsageExtension()
second_title: Aspose.Slides voor C++ API-referentie
description: Standaardconstructor.
type: docs
weight: 1
url: /nl/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() constructor


Standaardconstructor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Geëncodeerde gegevens van sleutelgebruiken. |
| critical | **bool** | Kritische aanduiding. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Sleutelgebruiken. |
| critical | **bool** | Kritische aanduiding. |

## Zie ook

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509KeyUsageExtension](../)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)