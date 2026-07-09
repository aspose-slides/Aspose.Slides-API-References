---
title: HandleRepeatedSpaces
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Spécifie comment les caractères d'espace réguliers répétés doivent être gérés lors de l'exportation Markdown.
type: docs
url: /fr/com.aspose.slides/handlerepeatedspaces/
---
**Héritage :**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Spécifie comment les caractères d'espace réguliers répétés doivent être gérés lors de l'exportation Markdown.
## Champs

| Champ | Description |
| --- | --- |
| [None](#None) | Tous les espaces sont conservés comme des caractères d'espace réguliers sans aucune modification. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Convertit les séquences de deux espaces réguliers ou plus consécutifs en alternant entre des caractères d'espace réguliers et des entités d'espace insécable NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Convertit les séquences de deux espaces réguliers ou plus consécutifs en conservant le premier espace comme caractère d'espace régulier et en remplaçant tous les espaces suivants par des entités d'espace insécable NBSP. |
### None {#None}
```
public static final int None
```

Tous les espaces sont conservés comme des caractères d'espace réguliers sans aucune modification. Aucune transformation n'est appliquée, et les espaces consécutifs multiples sont exportés tels quels.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Convertit les séquences de deux espaces réguliers ou plus consécutifs en alternant entre des caractères d'espace réguliers et des entités d'espace insécable NBSP. Le premier espace est toujours conservé comme espace régulier.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Convertit les séquences de deux espaces réguliers ou plus consécutifs en conservant le premier espace comme caractère d'espace régulier et en remplaçant tous les espaces suivants par des entités d'espace insécable NBSP.