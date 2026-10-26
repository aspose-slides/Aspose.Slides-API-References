---
title: IMathBarFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math bar
type: docs
url: /vi/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Cho phép tạo một thanh toán toán học

--------------------

Để khả năng tương thích COM
## Phương thức

| Method | Description |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Create a math bar by applying to the element |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Create a math bar by applying to the element |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```


Tạo một thanh toán toán học bằng cách áp dụng vào phần tử

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng thanh |

**Giá trị trả về:**
[IMathBar](../../com.aspose.slides/imathbar) - phần tử thanh toán toán mới
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```


Tạo một thanh toán toán học bằng cách áp dụng vào phần tử

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử toán học để áp dụng thanh |
| position | int | Vị trí của thanh |

**Giá trị trả về:**
[IMathBar](../../com.aspose.slides/imathbar) - phần tử thanh toán toán mới