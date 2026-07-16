---
title: DigitalSignature()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouvel objet DigitalSignature avec le certificat spécifié.
type: docs
weight: 66
url: /fr/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) constructeur


Crée un nouvel objet [DigitalSignature](../) avec le certificat spécifié.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Certificat qui sera utilisé pour signer la présentation. |

## DigitalSignature::DigitalSignature(System::String, System::String) constructeur


Crée un nouvel objet [DigitalSignature](../) avec le chemin du fichier de certificat spécifié et le mot de passe.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Chemin du fichier contenant le certificat. |
| password | [System::String](../../../system/string/) | Mot de passe requis pour accéder au certificat. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Classe [DigitalSignature](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)