---
title: IMathLimitFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe om IMathLimit te maken
type: docs
url: /nl/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Staat toe om IMathLimit te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Maakt IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt IMathLimit met limiet onderaan |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Maakt IMathLimit

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de limiet toe te passen |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limiet element |
| upperLimit | boolean | Stelt de plaatsing van de limiet bovenaan in |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nieuwe wiskundige limiet
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Maakt IMathLimit met limiet onderaan

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de limiet toe te passen |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limiet element |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nieuwe wiskundige limiet