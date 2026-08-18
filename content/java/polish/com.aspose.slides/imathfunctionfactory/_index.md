---
title: IMathFunctionFactory
second_title: Aspose.Slides for Java – Referencja API
description: Umożliwia tworzenie funkcji matematycznej
type: docs
url: /pl/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Umożliwia tworzenie funkcji matematycznej

--------------------

Dla zgodności z COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates math function |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Creates math function |
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
[IMathFunction](../../com.aspose.slides/imathfunction) - nowa funkcja matematyczna
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
[IMathFunction](../../com.aspose.slides/imathfunction) - nowa funkcja matematyczna