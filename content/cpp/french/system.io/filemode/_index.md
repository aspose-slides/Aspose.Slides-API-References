---
title: FileMode
second_title: Référence de l'API Aspose.Slides for C++
description: Spécifie comment un fichier doit être ouvert.
type: docs
weight: 508
url: /fr/system.io/filemode/
---
## FileMode enum


Spécifie comment un fichier doit être ouvert.

```cpp
enum class FileMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| CreateNew | 1 | Crée un nouveau fichier. Si le fichier existe déjà, une exception est levée. |
| Create | 2 | Crée un nouveau fichier. Si le fichier existe déjà, il est écrasé. |
| Open | 3 | Ouvre un fichier existant. Si le fichier n'existe pas, une exception est levée. |
| OpenOrCreate | 4 | Ouvre un fichier existant ou crée un nouveau s'il n'existe pas. |
| Truncate | 5 | Ouvre un fichier existant et le tronque afin qu'il soit vide. Si le fichier n'existe pas, une exception est levée. |
| Append | 6 | Ouvre un fichier existant et se positionne à la fin, ou crée un nouveau s'il n'existe pas. |

## Voir aussi

* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)