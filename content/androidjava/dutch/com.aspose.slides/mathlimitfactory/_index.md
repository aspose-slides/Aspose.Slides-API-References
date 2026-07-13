---
title: MathLimitFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe IMathLimit te maken
type: docs
url: /nl/com.aspose.slides/mathlimitfactory/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)  
```
public class MathLimitFactory implements IMathLimitFactory
```

Staat toe IMathLimit te maken

--------------------

Voor COM-compatibiliteit
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Methoden

| Method | Beschrijving |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Maakt IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt IMathLimit met limiet onderaan |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Maakt IMathLimit

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de limiet toe te passen |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limiet-element |
| upperLimit | boolean | Stelt de plaatsing van de limiet bovenaan in |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) – nieuwe wiskundige limiet
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Maakt IMathLimit met limiet onderaan

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de limiet toe te passen |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limiet-element |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) – nieuwe wiskundige limiet