---
title: MathNaryOperatorFactory
second_title: Aspose.Slides Android için Java API Referansı
description: IMathNaryOperator oluşturulmasına izin verir
type: docs
url: /tr/com.aspose.slides/mathnaryoperatorfactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

IMathNaryOperator oluşturulmasına izin verir

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator oluşturur |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator oluşturur |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | IMathNaryOperator oluşturur |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


IMathNaryOperator oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operatorSymbol | char | Operatör işareti |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Operatörü uygulamak için temel argüman |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alt limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Üst limit |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - yeni IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


IMathNaryOperator oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operatorSymbol | char | Operatör işareti |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Operatörü uygulamak için temel argüman |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alt limit |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - yeni IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


IMathNaryOperator oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operatorSymbol | char | Operatör işareti |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Operatörü uygulamak için temel argüman |

**Döndürür:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - yeni IMathNaryOperator