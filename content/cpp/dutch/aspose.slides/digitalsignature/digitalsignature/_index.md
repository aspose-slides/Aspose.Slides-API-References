---
title: DigitalSignature()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw DigitalSignature-object aan met het opgegeven certificaat.
type: docs
weight: 66
url: /nl/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) constructor

Maakt een nieuw [DigitalSignature](../) object aan met het opgegeven certificaat.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Certificaat dat zal worden gebruikt om de presentatie te ondertekenen. |

## DigitalSignature::DigitalSignature(System::String, System::String) constructor

Maakt een nieuw [DigitalSignature](../) object aan met het opgegeven certificaatbestandspad en wachtwoord.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Pad naar het bestand met certificaat. |
| password | [System::String](../../../system/string/) | Wachtwoord dat nodig is om toegang te krijgen tot het certificaat. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Klasse [DigitalSignature](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)