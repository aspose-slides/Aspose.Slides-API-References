---
title: MathFunctionFactory
second_title: Aspose.Slides cho Android qua Tham khảo API Java
description: Cho phép tạo một hàm toán học
type: docs
url: /vi/com.aspose.slides/mathfunctionfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các Giao diện được triển khai:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Cho phép tạo một hàm toán học

--------------------

Để tương thích COM
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo hàm toán học |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Tạo hàm toán học |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Tạo hàm toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử được dùng làm tên hàm |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử được dùng làm đối số hàm |

**Giá trị trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - hàm toán học mới
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Tạo hàm toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| funcName | java.lang.String | Tên hàm |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử được dùng làm đối số hàm |

**Giá trị trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - hàm toán học mới