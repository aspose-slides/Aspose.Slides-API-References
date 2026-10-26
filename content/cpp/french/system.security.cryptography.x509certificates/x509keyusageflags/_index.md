---
title: X509KeyUsageFlags
second_title: Référence API Aspose.Slides pour C++
description: Définit comment la clé du certificat peut être utilisée.
type: docs
weight: 274
url: /fr/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum


Définit comment la clé du certificat peut être utilisée.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Aucun paramètre d'utilisation de la clé. |
| EncipherOnly | 1 | La clé ne peut être utilisée que pour le chiffrement. |
| CrlSign | 2 | La clé peut être utilisée pour signer une liste de révocation de certificats. |
| KeyCertSign | 4 | La clé peut être utilisée pour signer des certificats. |
| KeyAgreement | 8 | La clé peut être utilisée pour établir un accord de clé. |
| DataEncipherment | 16 | La clé peut être utilisée pour le chiffrement de données. |
| KeyEncipherment | 32 | La clé peut être utilisée pour le chiffrement de clé. |
| NonRepudiation | 64 | La clé peut être utilisée pour l'authentification. |
| DigitalSignature | 128 | La clé peut être utilisée comme signature numérique. |
| DecipherOnly | 32768 | La clé ne peut être utilisée que pour le déchiffrement. |

## Voir aussi

* Espace de noms [System::Security::Cryptography::X509Certificates](../)
* Bibliothèque [Aspose.Slides](../../)