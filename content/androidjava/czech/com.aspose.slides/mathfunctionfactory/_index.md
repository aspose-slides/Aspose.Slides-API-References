---
title: MathFunctionFactory
second_title: Aspose.Slides pro Android přes Java API Reference
description: Umožňuje vytvořit matematickou funkci
type: docs
url: /cs/com.aspose.slides/mathfunctionfactory/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Umožňuje vytvořit matematickou funkci

--------------------

Pro kompatibilitu s COM
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytváří matematickou funkci |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Vytváří matematickou funkci |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Vytváří matematickou funkci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Prvek použitý jako název funkce |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Prvek použitý jako argument funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nová matematická funkce
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Vytváří matematickou funkci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| funcName | java.lang.String | Název funkce |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Prvek použitý jako argument funkce |

**Vrací:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nová matematická funkce