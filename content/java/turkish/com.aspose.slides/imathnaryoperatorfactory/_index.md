---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create IMathNaryOperator
type: docs
url: /tr/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

IMathNaryOperator oluşturulmasına izin verir

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator oluşturur |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator oluşturur |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | IMathNaryOperator oluşturur |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

IMathNaryOperator oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operatorSymbol | char | Operatör işareti |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Operatörü uygulamak için temel argüman |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alt sınır |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Üst sınır |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - yeni IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

IMathNaryOperator oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operatorSymbol | char | Operatör işareti |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Operatörü uygulamak için temel argüman |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alt sınır |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - yeni IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

IMathNaryOperator oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operatorSymbol | char | Operatör işareti |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Operatörü uygulamak için temel argüman |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - yeni IMathNaryOperator