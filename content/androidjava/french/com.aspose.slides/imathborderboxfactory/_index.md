---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Permet de créer une boîte de bordure mathématique
type: docs
url: /fr/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Permet de créer une boîte de bordure mathématique

--------------------

Pour la compatibilité COM
## Méthodes

| Method | Description |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Crée une boîte de bordure mathématique en l'appliquant à l'élément |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Crée une boîte de bordure mathématique en l'appliquant à l'élément |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Crée une boîte de bordure mathématique en l'appliquant à l'élément

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer la boîte de bordure |

**Retour :**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nouvel élément de boîte de bordure
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Crée une boîte de bordure mathématique en l'appliquant à l'élément

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer la boîte de bordure |
| hideTop | boolean | Masquer le bord supérieur |
| hideBottom | boolean | Masquer le bord inférieur |
| hideLeft | boolean | Masquer le bord gauche |
| hideRight | boolean | Masquer le bord droit |
| strikethroughHorizontal | boolean | Barre horizontale de la boîte de bordure |
| strikethroughVertical | boolean | Barre verticale de la boîte de bordure |
| strikethroughBottomLeftToTopRight | boolean | Barre de la boîte de bordure du coin inférieur gauche au coin supérieur droit |
| strikethroughTopLeftToBottomRight | boolean | Barre de la boîte de bordure du coin supérieur gauche au coin inférieur droit |

**Retour :**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nouvel élément de boîte de bordure