---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Cho phép tạo một phân số toán học
type: docs
url: /vi/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Cho phép tạo một phân số toán học

--------------------

Để tương thích COM
## Phương thức

| Method | Description |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Tạo một phân số toán học |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo một phân số toán học |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Tạo một phân số toán học

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Tử số |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mẫu số |
| fractionType | int | Kiểu phân số |

**Giá trị trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số toán học mới [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Tạo một phân số toán học

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Tử số |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mẫu số |

**Giá trị trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số toán học mới [IMathFraction](../../com.aspose.slides/imathfraction)