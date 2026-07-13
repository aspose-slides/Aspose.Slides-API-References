---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt toe een wiskundige functie te maken
type: docs
url: /nl/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Stelt toe een wiskundige functie te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt wiskundige functie |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Maakt wiskundige functie |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Maakt wiskundige functie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Element gebruikt als functienaam |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element gebruikt als functie-argument |

**Retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nieuwe wiskundige functie
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Maakt wiskundige functie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| funcName | java.lang.String | Functienaam |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element gebruikt als functie-argument |

**Retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nieuwe wiskundige functie