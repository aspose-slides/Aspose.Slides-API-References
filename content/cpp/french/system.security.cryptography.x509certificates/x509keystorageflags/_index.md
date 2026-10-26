---
title: X509KeyStorageFlags
second_title: Référence API Aspose.Slides pour C++
description: Définit comment stocker la clé.
type: docs
weight: 261
url: /fr/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum

Définit comment stocker la clé.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| DefaultKeySet | 0 | Utilise le jeu de clés par défaut. |
| UserKeySet | 1 | Utilise le magasin associé à l'utilisateur au lieu de celui local à la machine. |
| MachineKeySet | 2 | Utilise le magasin local de la machine au lieu de celui de l'utilisateur. |
| Exportable | 4 | Marque les clés importées comme exportables. |
| UserProtected | 8 | Notifie l'utilisateur que la clé est utilisée. |
| PersistKeySet | 16 | La clé est persistée lors de l'importation du certificat. |

## Voir aussi

* Espace de noms [System::Security::Cryptography::X509Certificates](../)
* Bibliothèque [Aspose.Slides](../../)