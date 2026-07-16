---
title: HandleRepeatedSpaces
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie comment les caractères d'espace ordinaires répétés doivent être traités lors de l'exportation Markdown.
type: docs
weight: 937
url: /fr/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

Spécifie comment les caractères d'espace ordinaires répétés doivent être traités lors de l'exportation Markdown.

```cpp
enum class HandleRepeatedSpaces
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Tous les espaces sont conservés en tant que caractères d'espace ordinaires sans aucune modification. Aucune transformation n'est appliquée, et les espaces consécutifs multiples sont exportés tels quels. |
| AlternateSpacesToNbsp | 1 | Convertit les séquences de deux espaces ordinaires ou plus consécutifs en alternant entre des caractères d'espace ordinaires et des entités d'espace insécable (**&nbsp;**). Le premier espace est toujours conservé comme espace ordinaire. |
| MultipleSpacesToNbsp | 2 | Convertit les séquences de deux espaces ordinaires ou plus consécutifs en conservant le premier espace comme caractère d'espace ordinaire et en remplaçant tous les espaces suivants par des entités d'espace insécable (**&nbsp;**). |

## Voir aussi

* Espace de noms [Aspose::Slides::Export](../)
* Bibliothèque [Aspose.Slides](../../)