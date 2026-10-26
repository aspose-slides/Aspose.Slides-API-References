---
title: IMathFunctionFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math function
type: docs
url: /vi/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Cho phép tạo một hàm toán học

--------------------

Để tương thích COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo hàm toán học |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Tạo hàm toán học |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

Tạo hàm toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử được sử dụng làm tên hàm |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử được sử dụng làm đối số hàm |

**Kết quả:**
[IMathFunction](../../com.aspose.slides/imathfunction) - hàm toán học mới
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

Tạo hàm toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| funcName | java.lang.String | Tên hàm |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử được sử dụng làm đối số hàm |

**Kết quả:**
[IMathFunction](../../com.aspose.slides/imathfunction) - hàm toán học mới