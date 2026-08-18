---
title: MathFunctionFactory
second_title: Aspose.Slides dla Java API
description: Umożliwia utworzenie funkcji matematycznej
type: docs
url: /pl/com.aspose.slides/mathfunctionfactory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Umożliwia utworzenie funkcji matematycznej

--------------------

Dla kompatybilności z COM
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy funkcję matematyczną |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Tworzy funkcję matematyczną |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Tworzy funkcję matematyczną

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Element używany jako nazwa funkcji |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element używany jako argument funkcji |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nowa funkcja matematyczna
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Tworzy funkcję matematyczną

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| funcName | java.lang.String | Nazwa funkcji |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element używany jako argument funkcji |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nowa funkcja matematyczna