---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math function
type: docs
url: /pl/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Umożliwia tworzenie funkcji matematycznej

--------------------

Dla kompatybilności COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy funkcję matematyczną |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Tworzy funkcję matematyczną |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Tworzy funkcję matematyczną

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Element używany jako nazwa funkcji |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element używany jako argument funkcji |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nową funkcję matematyczną
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Tworzy funkcję matematyczną

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| funcName | java.lang.String | Nazwa funkcji |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element używany jako argument funkcji |

**Zwraca:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nową funkcję matematyczną