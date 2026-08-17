---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description: Permet de créer un caractère de groupement mathématique
type: docs
url: /fr/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Permet de créer un caractère de groupement mathématique

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Crée un caractère de groupement mathématique

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer le caractère de groupement |
| character | char | caractère de groupement |
| position | int | position du caractère de groupement |
| verticalJustification | int | justification verticale |

**Renvoie:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nouveau élément de caractère de groupement
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Crée un caractère de groupement mathématique

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer le caractère de groupement |

**Renvoie:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nouveau élément de caractère de groupement