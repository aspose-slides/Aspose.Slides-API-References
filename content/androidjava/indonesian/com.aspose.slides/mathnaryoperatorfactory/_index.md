---
title: MathNaryOperatorFactory
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mengizinkan pembuatan IMathNaryOperator
type: docs
url: /id/com.aspose.slides/mathnaryoperatorfactory/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Mengizinkan pembuatan IMathNaryOperator

--------------------

Untuk kompatibilitas COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Membuat IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Membuat IMathNaryOperator

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operatorSymbol | char | Tanda operator |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dasar untuk menerapkan operator |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas bawah |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas atas |

**Mengembalikan:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Membuat IMathNaryOperator

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operatorSymbol | char | Tanda operator |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dasar untuk menerapkan operator |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas bawah |

**Mengembalikan:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Membuat IMathNaryOperator

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operatorSymbol | char | Tanda operator |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dasar untuk menerapkan operator |

**Mengembalikan:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator