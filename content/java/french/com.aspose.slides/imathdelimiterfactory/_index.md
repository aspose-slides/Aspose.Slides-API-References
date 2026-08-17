---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math delimiter
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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer le délimiteur |

**Retour:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nouveau délimiteur mathématique
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Créer un délimiteur mathématique en l'appliquant à l'élément

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | éléments mathématiques auxquels appliquer le délimiteur |

**Retour:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nouveau délimiteur mathématique