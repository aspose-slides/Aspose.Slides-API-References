---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android Java API hivatkozása
description: Lehetővé teszi matematikai függvény létrehozását
type: docs
url: /hu/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Lehetővé teszi matematikai függvény létrehozását

--------------------

A COM kompatibilitáshoz
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehozza a matematikai függvényt |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Létrehozza a matematikai függvényt |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

Létrehozza a matematikai függvényt

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | A függvény nevéhez használt elem |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | A függvény argumentumaként használt elem |

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - új matematikai függvény
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

Létrehozza a matematikai függvényt

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| funcName | java.lang.String | Függvény neve |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | A függvény argumentumaként használt elem |

**Visszatér:**
[IMathFunction](../../com.aspose.slides/imathfunction) - új matematikai függvény