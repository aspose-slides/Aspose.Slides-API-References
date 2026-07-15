---
title: MathLimitFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo IMathLimit
type: docs
url: /vi/com.aspose.slides/mathlimitfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Cho phép tạo IMathLimit

--------------------

Để tương thích COM
## Phương thức tạo

| Phương thức tạo | Mô tả |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Tạo IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo IMathLimit với giới hạn ở dưới |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Tạo IMathLimit

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ bản để áp dụng giới hạn |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử giới hạn |
| upperLimit | boolean | Đặt vị trí của giới hạn ở trên |

**Trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - giới hạn toán học mới
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Tạo IMathLimit với giới hạn ở dưới

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ bản để áp dụng giới hạn |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử giới hạn |

**Trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - giới hạn toán học mới