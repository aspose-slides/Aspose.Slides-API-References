---
title: IMathSuperscriptElement
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định đối tượng chỉ số trên, bao gồm một cơ sở và một chỉ số trên có kích thước giảm, đặt phía trên và bên phải
type: docs
url: /vi/com.aspose.slides/imathsuperscriptelement/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Xác định đối tượng chỉ số trên, bao gồm một cơ sở và một chỉ số trên có kích thước giảm, đặt phía trên và bên phải

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getSuperscript()](#getSuperscript--) | Chỉ số trên |
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
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Chỉ số trên

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)