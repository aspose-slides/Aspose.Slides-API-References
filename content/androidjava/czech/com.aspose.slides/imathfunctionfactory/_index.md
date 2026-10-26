---
title: IMathFunctionFactory
second_title: Aspose.Slides pro Android přes Java API Reference
description: Umožňuje vytvářet matematickou funkci
type: docs
url: /cs/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Umožňuje vytvářet matematickou funkci

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytváří matematickou funkci |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Vytváří matematickou funkci |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Vytváří matematickou funkci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Prvek použitý jako název funkce |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Prvek použitý jako argument funkce |

**Návratová hodnota:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nová matematická funkce
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Vytváří matematickou funkci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| funcName | java.lang.String | Název funkce |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Prvek použitý jako argument funkce |

**Návratová hodnota:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nová matematická funkce