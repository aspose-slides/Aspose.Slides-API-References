---
title: NewLineHandling
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie comment gérer les sauts de ligne.
type: docs
weight: 690
url: /fr/system.xml/newlinehandling/
---
## NewLineHandling enum

Spécifie comment gérer les sauts de ligne.

```cpp
enum class NewLineHandling
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Replace | 0 | Les caractères de nouvelle ligne sont remplacés pour correspondre au caractère spécifié dans la valeur [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/). |
| Entitize | 1 | Les caractères de nouvelle ligne sont entitisés. Ce réglage conserve tous les caractères lorsque la sortie est lue par un [XmlReader](../xmlreader/) normalisateur. |
| None | 2 | Les caractères de nouvelle ligne restent inchangés. La sortie est identique à l’entrée. |

## Voir aussi

* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)