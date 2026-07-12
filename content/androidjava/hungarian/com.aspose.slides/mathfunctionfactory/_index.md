---
title: MathFunctionFactory
second_title: Aspose.Slides for Android a Java API hivatkozásban
description: Lehetővé teszi matematikai függvény létrehozását
type: docs
url: /hu/com.aspose.slides/mathfunctionfactory/
---
**Öröklés:**  
java.lang.Object

**Minden megvalósított interfész:**  
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)  
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Lehetővé teszi matematikai függvény létrehozását

--------------------

COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehozza a matematikai függvényt |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Létrehozza a matematikai függvényt |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```

### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

Létrehozza a matematikai függvényt

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | A függvény névként használt elem |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Az argumentumként használt elem |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - új matematikai függvény
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

Létrehozza a matematikai függvényt

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| funcName | java.lang.String | Függvény neve |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Az argumentumként használt elem |

**Visszatérési érték:**
[IMathFunction](../../com.aspose.slides/imathfunction) - új matematikai függvény