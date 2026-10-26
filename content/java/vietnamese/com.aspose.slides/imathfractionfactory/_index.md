---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math fraction
type: docs
url: /vi/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Cho phép tạo một phân số toán học

--------------------

Để tương thích với COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Tạo một phân số toán học |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo một phân số toán học |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Tạo một phân số toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Tử số |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mẫu số |
| fractionType | int | Kiểu phân số |

**Trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Phân số toán học mới [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Tạo một phân số toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Tử số |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mẫu số |

**Trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Phân số toán học mới [IMathFraction](../../com.aspose.slides/imathfraction)