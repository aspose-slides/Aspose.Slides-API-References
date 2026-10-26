---
title: X509KeyUsageExtension()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruttore predefinito.
type: docs
weight: 1
url: /it/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() costruttore

Costruttore predefinito.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) costruttore

Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Dati codificati degli usi della chiave. |
| critical | **bool** | Segno di criticità. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) costruttore

Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Usi della chiave. |
| critical | **bool** | Segno di criticità. |

## Vedi anche

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509KeyUsageExtension](../)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)