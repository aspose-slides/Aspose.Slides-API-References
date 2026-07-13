---
title: MathFunctionFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe een wiskundige functie te maken
type: docs
url: /nl/com.aspose.slides/mathfunctionfactory/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Staat toe een wiskundige functie te maken

--------------------

Voor COM-compatibiliteit
## Constructoren

| Constructor | Description |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Methoden

| Method | Description |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt wiskundige functie |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Maakt wiskundige functie |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Maakt wiskundige functie

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Element dat als functienaam wordt gebruikt |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element dat als functie-argument wordt gebruikt |

**Retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nieuwe wiskundige functie
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Maakt wiskundige functie

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | java.lang.String | Functienaam |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element dat als functie-argument wordt gebruikt |

**Retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nieuwe wiskundige functie