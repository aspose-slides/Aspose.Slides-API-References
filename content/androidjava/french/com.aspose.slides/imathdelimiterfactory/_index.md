---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Permet de créer un délimiteur mathématique
type: docs
url: /fr/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Permet de créer un délimiteur mathématique

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Créer un délimiteur mathématique en l'appliquant à l'élément |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Créer un délimiteur mathématique en l'appliquant à l'élément |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

Créer un délimiteur mathématique en l'appliquant à l'élément

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply delimiter |

**Renvoie :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nouveau délimiteur mathématique
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Créer un délimiteur mathématique en l'appliquant à l'élément

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | math elements to apply delimiter |

**Renvoie :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nouveau délimiteur mathématique