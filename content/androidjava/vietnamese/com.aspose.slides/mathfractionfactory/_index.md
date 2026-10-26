---
title: MathFractionFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo một phân số toán học
type: docs
url: /vi/com.aspose.slides/mathfractionfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được triển khai:**
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

Cho phép tạo một phân số toán học

--------------------

Đối với khả năng tương thích COM
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Tạo một phân số toán học |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo một phân số toán học |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```


### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Tạo một phân số toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Tử số |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mẫu số |
| fractionType | int | Kiểu phân số |

**Trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số toán học mới
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Tạo một phân số toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Tử số |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mẫu số |

**Trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số toán học mới