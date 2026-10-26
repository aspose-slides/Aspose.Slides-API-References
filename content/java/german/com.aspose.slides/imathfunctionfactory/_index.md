---
title: IMathFunctionFactory
second_title: Aspose.Slides for Java API Reference
description: Ermöglicht das Erstellen einer mathematischen Funktion
type: docs
url: /de/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Ermöglicht das Erstellen einer mathematischen Funktion

--------------------

Für COM-Kompatibilität
## Methoden

| Method | Beschreibung |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt eine mathematische Funktion |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Erstellt eine mathematische Funktion |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Erstellt eine mathematische Funktion

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Als Funktionsname verwendetes Element |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Als Funktionsargument verwendetes Element |

**Rückgabewert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - neue mathematische Funktion
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Erstellt eine mathematische Funktion

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| funcName | java.lang.String | Funktionsname |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Als Funktionsargument verwendetes Element |

**Rückgabewert:**
[IMathFunction](../../com.aspose.slides/imathfunction) - neue mathematische Funktion