---
title: X509Extension()
second_title: Référence de l'API Aspose.Slides pour C++
description: Constructeur.
type: docs
weight: 1
url: /fr/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Données encodées associées au certificat. |
| critical | **bool** | Indicateur de criticité. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) identifiant associé à l'extension. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données brutes associées au certificat. |
| critical | **bool** | Indicateur de criticité. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identifiant associé à l'extension. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données brutes associées au certificat. |
| critical | **bool** | Indicateur de criticité. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Classe [X509Extension](../)
* Classe [Oid](../../../system.security.cryptography/oid/)
* Classe [String](../../../system/string/)
* Espace de noms [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)