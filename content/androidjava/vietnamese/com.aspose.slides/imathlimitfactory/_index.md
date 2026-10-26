---
title: IMathLimitFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo IMathLimit
type: docs
url: /vi/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Cho phép tạo IMathLimit

--------------------

Đối với tính tương thích COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Tạo IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo IMathLimit với giới hạn ở phía dưới |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

Tạo IMathLimit

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ bản để áp dụng giới hạn |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử giới hạn |
| upperLimit | boolean | Đặt vị trí của giới hạn lên trên |

**Giá trị trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - giới hạn toán học mới
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

Tạo IMathLimit với giới hạn ở phía dưới

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Đối số cơ bản để áp dụng giới hạn |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử giới hạn |

**Giá trị trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - giới hạn toán học mới