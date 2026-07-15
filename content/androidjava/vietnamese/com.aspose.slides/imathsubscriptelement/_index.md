---
title: IMathSubscriptElement
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định đối tượng chỉ số dưới, bao gồm một cơ sở và một chỉ số dưới có kích thước giảm, được đặt phía dưới và bên phải.
type: docs
url: /vi/com.aspose.slides/imathsubscriptelement/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Xác định đối tượng chỉ số dưới, bao gồm một cơ sở và một chỉ số dưới có kích thước giảm, được đặt phía dưới và bên phải.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getSubscript()](#getSubscript--) | Chỉ số dưới |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Đối số cơ sở

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
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