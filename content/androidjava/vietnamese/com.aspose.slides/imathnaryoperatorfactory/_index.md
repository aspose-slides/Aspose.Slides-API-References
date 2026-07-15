---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Cho phép tạo IMathNaryOperator
type: docs
url: /vi/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Cho phép tạo IMathNaryOperator

--------------------

Để tương thích COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Creates IMathNaryOperator

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operatorSymbol | char | Ký hiệu toán tử |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ sở để áp dụng toán tử |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn dưới |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn trên |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Creates IMathNaryOperator

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operatorSymbol | char | Ký hiệu toán tử |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ sở để áp dụng toán tử |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn dưới |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Creates IMathNaryOperator

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operatorSymbol | char | Ký hiệu toán tử |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ sở để áp dụng toán tử |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator