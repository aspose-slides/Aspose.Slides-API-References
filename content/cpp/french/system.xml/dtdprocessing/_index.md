---
title: DtdProcessing
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie les options de traitement des DTD. L'énumération DtdProcessing est utilisée par la classe XmlReaderSettings.
type: docs
weight: 638
url: /fr/system.xml/dtdprocessing/
---
## DtdProcessing enum

Spécifie les options de traitement des DTD. L'énumération DtdProcessing est utilisée par la classe [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Prohibit | 0 | Indique que lorsqu'un DTD est rencontré, une XmlException est levée avec un message indiquant que les DTD sont interdits. C'est le comportement par défaut. |
| Ignore | 1 | Force l'élément DOCTYPE à être ignoré. Aucun traitement de DTD n'est effectué, et le DTD/DOCTYPE est perdu lors de la sortie. |
| Parse | 2 | Utilisé pour l'analyse des DTD. |

## Voir aussi

* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)