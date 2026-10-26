---
title: X509KeyUsageExtension()
second_title: Référence API Aspose.Slides pour C++
description: Constructeur par défaut.
type: docs
weight: 1
url: /fr/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() constructeur


Constructeur par défaut.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Données encodées des usages de clé. |
| critical | **bool** | Indicateur de criticité. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Usages de clé. |
| critical | **bool** | Indicateur de criticité. |

## Voir aussi

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [X509KeyUsageExtension](../)
* Classe [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Espace de noms [System::Security::Cryptography::X509Certificates](../../)
* Bibliothèque [Aspose.Slides](../../../)