---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Gör det möjligt att skapa en matematisk funktion
type: docs
url: /sv/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Gör det möjligt att skapa en matematisk funktion

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar matematisk funktion |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Skapar matematisk funktion |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
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
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

Skapar en matematisk funktion

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| funcName | java.lang.String | Funktionsnamn |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element som används som funktionsargument |

**Returnerar:**
[IMathFunction](../../com.aspose.slides/imathfunction) - ny matematisk funktion