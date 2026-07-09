---
title: MathBorderBoxFactory
second_title: Référence API Java via Aspose.Slides pour Android
description: Permet de créer une boîte de bordure mathématique
type: docs
url: /fr/com.aspose.slides/mathborderboxfactory/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Permet de créer une boîte de bordure mathématique

--------------------

Pour la compatibilité COM
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Créer une boîte de bordure mathématique en l'appliquant à l'élément |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Créer une boîte de bordure mathématique en l'appliquant à l'élément |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Créer une boîte de bordure mathématique en l'appliquant à l'élément

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer la boîte de bordure |

**Renvoie :**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nouvel élément de boîte de bordure
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Créer une boîte de bordure mathématique en l'appliquant à l'élément

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer la boîte de bordure |
| hideTop | boolean | Masquer le bord supérieur |
| hideBottom | boolean | Masquer le bord inférieur |
| hideLeft | boolean | Masquer le bord gauche |
| hideRight | boolean | Masquer le bord droit |
| strikethroughHorizontal | boolean | Trait de travers horizontal de la boîte de bordure |
| strikethroughVertical | boolean | Trait de travers vertical de la boîte de bordure |
| strikethroughBottomLeftToTopRight | boolean | Trait de travers bas-gauche vers haut-droit de la boîte de bordure |
| strikethroughTopLeftToBottomRight | boolean | Trait de travers haut-gauche vers bas-droit de la boîte de bordure |

**Renvoie :**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nouvel élément de boîte de bordure