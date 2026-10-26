---
title: FileShare
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie le type d'accès que d'autres objets FileStream peuvent avoir à un fichier en cours d'ouverture.
type: docs
weight: 534
url: /fr/system.io/fileshare/
---
## FileShare enum

Spécifie le type d'accès que d'autres objets [FileStream](../filestream/) peuvent avoir à un fichier en cours d'ouverture.

```cpp
enum class FileShare
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Aucun accès. |
| Read | 1 | Accès en lecture seule. |
| Write | 2 | Accès en écriture seule. |
| ReadWrite | 3 | Accès en lecture et écriture. |
| Delete | 4 | Le fichier peut être supprimé. |
| Inheritable | 16 | Rend le handle du fichier héritable par les processus enfants. |

## Voir aussi

* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)