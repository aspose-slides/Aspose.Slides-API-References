---
title: DigitalSignature()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nový objekt DigitalSignature se zadaným certifikátem.
type: docs
weight: 66
url: /cs/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) konstruktor


Vytvoří nový objekt [DigitalSignature](../) se zadaným certifikátem.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Certifikát, který bude použit k podepsání prezentace. |

## DigitalSignature::DigitalSignature(System::String, System::String) konstruktor


Vytvoří nový objekt [DigitalSignature](../) se zadanou cestou k souboru certifikátu a heslem.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Cesta k souboru s certifikátem. |
| password | [System::String](../../../system/string/) | Heslo požadované pro přístup k certifikátu. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Třída [DigitalSignature](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)