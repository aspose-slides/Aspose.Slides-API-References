---
title: EncryptionPolicy
second_title: Référence de l'API Aspose.Slides pour C++
description: Énumère les politiques de chiffrement.
type: docs
weight: 53
url: /fr/system.net.security/encryptionpolicy/
---
## EncryptionPolicy enum

Énumère les politiques de chiffrement.

```cpp
enum class EncryptionPolicy
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| RequireEncryption | 0 | Exiger le chiffrement et ne jamais autoriser un chiffrement 'Null'. |
| AllowNoEncryption | 1 | Préférer utiliser le chiffrement complet mais un chiffrement 'Null' peut être utilisé si le serveur accepte. |
| NoEncryption | 2 | Autoriser aucun chiffrement et demander qu'un chiffrement 'Null' soit utilisé si l'autre point d'extrémité peut gérer un chiffrement 'Null'. |

## Voir aussi

* Espace de noms [System::Net::Security](../)
* Bibliothèque [Aspose.Slides](../../)