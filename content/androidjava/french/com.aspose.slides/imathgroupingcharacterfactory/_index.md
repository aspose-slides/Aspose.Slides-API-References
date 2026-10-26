---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides pour Android via la Référence de l'API Java
description: Permet de créer un caractère de regroupement mathématique
type: docs
url: /fr/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Permet de créer un caractère de regroupement mathématique

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Crée un caractère de regroupement mathématique |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Crée un caractère de regroupement mathématique |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
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
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nouvel élément de caractère de regroupement
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Crée un caractère de regroupement mathématique

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer le caractère de regroupement |

**Retour:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nouvel élément de caractère de regroupement