---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Cho phép tạo một hàm toán học
type: docs
url: /vi/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Cho phép tạo một hàm toán học

--------------------

Đối với khả năng tương thích COM
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

**Giá trị trả về:**
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

**Giá trị trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - hàm toán học mới