---
title: MathFunctionFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa en matematisk funktion
type: docs
url: /sv/com.aspose.slides/mathfunctionfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Tillåter att skapa en matematisk funktion

--------------------

För COM-kompatibilitet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar en matematisk funktion |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Skapar en matematisk funktion |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Skapar en matematisk funktion

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Element som används som funktionsnamn |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element som används som funktionsargument |

**Returnerar:**
[IMathFunction](../../com.aspose.slides/imathfunction) - ny matematisk funktion
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Skapar en matematisk funktion

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| funcName | java.lang.String | Funktionsnamn |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element som används som funktionsargument |

**Returnerar:**
[IMathFunction](../../com.aspose.slides/imathfunction) - ny matematisk funktion