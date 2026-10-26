---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định đối tượng Sub-Superscript, bao gồm một cơ sở và chỉ số dưới cùng và chỉ số trên được đặt bên phải của cơ sở.
type: docs
url: /vi/com.aspose.slides/imathrightsubsuperscriptelement/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Xác định đối tượng Sub-Superscript, bao gồm một cơ sở và chỉ số dưới cùng và chỉ số trên được đặt bên phải của cơ sở.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getSubscript()](#getSubscript--) | Đối số chỉ số dưới |
| [getSuperscript()](#getSuperscript--) | Đối số chỉ số trên |
| [getAlignScripts()](#getAlignScripts--) | Xác định việc căn chỉnh chỉ số dưới/ chỉ số trên. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Xác định việc căn chỉnh chỉ số dưới/ chỉ số trên. |
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
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Đối số chỉ số dưới

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Đối số chỉ số trên

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```

Xác định việc căn chỉnh chỉ số dưới/ chỉ số trên. Khi true, chỉ số dưới và chỉ số trên được căn chỉnh theo chiều ngang với nhau. Khi false, chúng được điều chỉnh theo hình dạng của cơ sở. Giá trị mặc định là false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Trả về:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```

Xác định việc căn chỉnh chỉ số dưới/ chỉ số trên. Khi true, chỉ số dưới và chỉ số trên được căn chỉnh theo chiều ngang với nhau. Khi false, chúng được điều chỉnh theo hình dạng của cơ sở. Giá trị mặc định là false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |