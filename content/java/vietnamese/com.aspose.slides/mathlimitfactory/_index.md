---
title: MathLimitFactory
second_title: Tham chiếu API Aspose.Slides cho Java
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

Đối với tính tương thích COM
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Tạo IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo IMathLimit với giới hạn ở phía dưới |
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
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ sở để áp dụng giới hạn |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử giới hạn |
| upperLimit | boolean | Đặt vị trí của giới hạn ở trên cùng |

**Giá trị trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - giới hạn toán học mới
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Tạo IMathLimit với giới hạn ở phía dưới

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ sở để áp dụng giới hạn |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử giới hạn |

**Giá trị trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - giới hạn toán học mới