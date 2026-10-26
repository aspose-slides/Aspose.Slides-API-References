---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Umožňuje vytvořit IMathNaryOperator
type: docs
url: /cs/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Umožňuje vytvořit IMathNaryOperator

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytváří IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytváří IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Vytváří IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Vytváří IMathNaryOperator

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char | Znak operátoru |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument pro použití operátoru |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolní mez |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Horní mez |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Vytváří IMathNaryOperator

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char | Znak operátoru |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument pro použití operátoru |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolní mez |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Vytváří IMathNaryOperator

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char | Znak operátoru |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument pro použití operátoru |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator