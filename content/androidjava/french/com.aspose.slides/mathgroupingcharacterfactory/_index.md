---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Permet de créer un caractère de regroupement mathématique
type: docs
url: /fr/com.aspose.slides/mathgroupingcharacterfactory/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Permet de créer un caractère de regroupement mathématique

--------------------

Pour la compatibilité COM
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```


### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Crée un caractère de regroupement mathématique

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer le caractère de regroupement |
| character | char | caractère de regroupement |
| position | int | position du caractère de regroupement |
| verticalJustification | int | justification verticale |

**Retour:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nouveau élément de caractère de regroupement
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Crée un caractère de regroupement mathématique

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer le caractère de regroupement |

**Retour:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nouveau élément de caractère de regroupement