---
title: ReadState
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie l'état du lecteur.
type: docs
weight: 703
url: /fr/system.xml/readstate/
---
## ReadState enum

Spécifie l'état du lecteur.

```cpp
enum class ReadState
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Initial | 0 | La méthode [XmlReader::Read](../xmlreader/read/) n'a pas été appelée. |
| Interactive | 1 | La méthode [XmlReader::Read](../xmlreader/read/) a été appelée. Des méthodes supplémentaires peuvent être appelées sur le lecteur. |
| Error | 2 | Une erreur s'est produite et empêche la poursuite de l'opération de lecture. |
| EndOfFile | 3 | La fin du fichier a été atteinte avec succès. |
| Closed | 4 | La méthode [XmlReader::Close](../xmlreader/close/) a été appelée. |

## Voir aussi

* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)