---
title: StringTrimming
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie comment les caractères doivent être tronqués d'une chaîne qui ne correspond pas à la forme de mise en page.
type: docs
weight: 495
url: /fr/system.drawing/stringtrimming/
---
## StringTrimming énumération

Spécifie comment les caractères doivent être tronqués d’une chaîne qui ne correspond pas à la forme de mise en page.

```cpp
enum class StringTrimming
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Pas de rognage. |
| Character | 1 | Rogner jusqu’au caractère le plus proche. |
| Word | 2 | Rogner jusqu’au mot le plus proche. |
| EllipsisCharacter | 3 | Rogner jusqu’au caractère le plus proche et insérer une ellipse à la fin de la chaîne. |
| EllipsisWord | 4 | Rogner jusqu’au mot le plus proche et insérer une ellipse à la fin de la chaîne. |
| EllipsisPath | 5 | Le centre est supprimé des lignes tronquées et remplacé par une ellipse. Conserver autant que possible le dernier segment de la ligne délimité par des barres obliques. |

## Voir aussi

* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)