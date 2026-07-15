---
title: MathSubscriptElement
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định đối tượng chỉ số dưới, bao gồm một cơ sở và một chỉ số con kích thước giảm được đặt phía dưới và bên phải.
type: docs
url: /vi/com.aspose.slides/mathsubscriptelement/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Xác định đối tượng chỉ số dưới, bao gồm một cơ sở và một chỉ số con có kích thước giảm đặt phía dưới và bên phải.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
```
## Các hàm tạo

| Constructor | Description |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Khởi tạo một thể hiện mới của lớp MathSubscriptElement. |
## Các phương thức

| Method | Description |
| --- | --- |
| [getSubscript()](#getSubscript--) | Chỉ số dưới |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


Khởi tạo một thể hiện mới của lớp MathSubscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Chỉ số dưới

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Lấy các phần tử con

**Trả về:**
com.aspose.slides.IMathElement[]