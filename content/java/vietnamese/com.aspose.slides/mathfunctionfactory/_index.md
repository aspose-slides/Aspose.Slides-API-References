---
title: MathFunctionFactory
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép tạo một hàm toán học
type: docs
url: /vi/com.aspose.slides/mathfunctionfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Cho phép tạo một hàm toán học

--------------------

Đối với khả năng tương thích COM
## Các hàm khởi tạo

| Constructor | Mô tả |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Các phương thức

| Method | Mô tả |
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

**Trả về:**
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

**Trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - hàm toán học mới