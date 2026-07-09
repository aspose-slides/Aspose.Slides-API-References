---
title: IMathFractionFactory
second_title: Aspose.Slides pour Android via Java API Reference
description: Permet de créer une fraction mathématique
type: docs
url: /fr/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Permet de créer une fraction mathématique

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Creates a math fraction |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates a math fraction |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Crée une fraction mathématique

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numérateur |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Dénominateur |
| fractionType | int | Type de fraction |

**Retour :**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nouvelle fraction mathématique [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Crée une fraction mathématique

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numérateur |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Dénominateur |

**Retour :**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nouvelle fraction mathématique [IMathFraction](../../com.aspose.slides/imathfraction)