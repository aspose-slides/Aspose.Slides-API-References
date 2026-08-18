---
title: IMathFunctionFactory
second_title: Aspose.Slides for Java API Reference
description: Lehetővé teszi egy matematikai függvény létrehozását
type: docs
url: /hu/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Lehetővé teszi egy matematikai függvény létrehozását

--------------------

A COM kompatibilitáshoz
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehoz egy matematikai függvényt |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Létrehoz egy matematikai függvényt |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Létrehoz egy matematikai függvényt

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | A függvény nevéként használt elem |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | A függvény argumentumaként használt elem |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - új matematikai függvény
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Létrehoz egy matematikai függvényt

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| funcName | java.lang.String | Függvény neve |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | A függvény argumentumaként használt elem |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - új matematikai függvény