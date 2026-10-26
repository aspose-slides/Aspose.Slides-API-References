---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Memungkinkan untuk membuat IMathNaryOperator
type: docs
url: /id/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Memungkinkan untuk membuat IMathNaryOperator

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Membuat IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
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
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
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
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Membuat IMathNaryOperator

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operatorSymbol | char | Tanda operator |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dasar untuk menerapkan operator |

**Mengembalikan:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator