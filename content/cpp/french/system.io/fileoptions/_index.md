---
title: FileOptions
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente des options avancées pour créer l'objet FileStream.
type: docs
weight: 521
url: /fr/system.io/fileoptions/
---
## FileOptions enum

Représente des options avancées pour créer l'objet [FileStream](../filestream/).

```cpp
enum class FileOptions
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Aucune option supplémentaire. |
| Encrypted | 16384 | Le fichier est chiffré. NOT IMPLEMENTED. |
| DeleteOnClose | 67108864 | Le fichier doit être automatiquement supprimé lorsqu'il n'est plus utilisé. |
| SequentialScan | 134217728 | Le fichier doit être accédé séquentiellement. |
| RandomAccess | 268435456 | Le fichier est accédé de façon aléatoire. |
| Asynchronous | 1073741824 | Le fichier peut être utilisé pour des opérations d'E/S asynchrones. |
| WriteThrough | n/a | Toutes les écritures doivent être dirigées directement vers le disque en contournant tout cache intermédiaire. |

## Voir aussi

* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)