---
title: MathFunctionFactory
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Ermöglicht das Erstellen einer mathematischen Funktion
type: docs
url: /de/com.aspose.slides/mathfunctionfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Ermöglicht das Erzeugen einer mathematischen Funktion

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt mathematische Funktion |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Erstellt mathematische Funktion |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Erstellt mathematische Funktion

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Als Funktionsnamen verwendetes Element |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Als Funktionsargument verwendetes Element |

**Rückgabewert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - neue mathematische Funktion
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Erstellt mathematische Funktion

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| funcName | java.lang.String | Funktionsname |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Als Funktionsargument verwendetes Element |

**Rückgabewert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - neue mathematische Funktion