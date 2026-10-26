---
title: MathNaryOperatorFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo IMathNaryOperator
type: docs
url: /vi/com.aspose.slides/mathnaryoperatorfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Cho phép tạo IMathNaryOperator

--------------------

Để tương thích COM
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Tạo IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Tạo IMathNaryOperator

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operatorSymbol | char | Dấu toán tử |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ bản để áp dụng toán tử |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn dưới |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn trên |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Tạo IMathNaryOperator

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operatorSymbol | char | Dấu toán tử |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ bản để áp dụng toán tử |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn dưới |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Tạo IMathNaryOperator

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operatorSymbol | char | Dấu toán tử |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ bản để áp dụng toán tử |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator