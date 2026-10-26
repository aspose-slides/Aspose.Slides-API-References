---
title: IMathBarFactory
second_title: Aspose.Slides for Java API Reference
description: Cho phép tạo một thanh số học
type: docs
url: /vi/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Cho phép tạo một thanh số học

--------------------

Đối với khả năng tương thích COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Tạo một thanh số học bằng cách áp dụng vào phần tử |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Tạo một thanh số học bằng cách áp dụng vào phần tử |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```

Tạo một thanh số học bằng cách áp dụng vào phần tử

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng thanh |

**Trả về:**
[IMathBar](../../com.aspose.slides/imathbar) - phần tử thanh số học mới
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```

Tạo một thanh số học bằng cách áp dụng vào phần tử

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng thanh |
| position | int | Vị trí của thanh |

**Trả về:**
[IMathBar](../../com.aspose.slides/imathbar) - phần tử thanh số học mới