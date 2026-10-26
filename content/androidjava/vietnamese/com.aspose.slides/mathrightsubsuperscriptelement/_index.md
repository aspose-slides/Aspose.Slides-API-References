---
title: MathRightSubSuperscriptElement
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Xác định đối tượng Sub-Superscript, bao gồm một cơ sở và chỉ số phụ cùng chỉ số trên được đặt bên phải cơ sở.
type: docs
url: /vi/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**All Implemented Interfaces:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Xác định đối tượng Sub-Superscript, bao gồm một cơ sở và chỉ số phụ cùng chỉ số trên được đặt bên phải cơ sở.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```
## Các hàm khởi tạo

| Constructor | Mô tả |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Khởi tạo một thể hiện mới của lớp MathRightSubSuperscriptElement. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSubscript()](#getSubscript--) | Tham số chỉ số phụ |
| [getSuperscript()](#getSuperscript--) | Tham số chỉ số trên |
| [getAlignScripts()](#getAlignScripts--) | Xác định việc căn chỉnh chỉ số phụ/chỉ số trên. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Xác định việc căn chỉnh chỉ số phụ/chỉ số trên. |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

Khởi tạo một thể hiện mới của lớp MathRightSubSuperscriptElement.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Tham số chỉ số phụ

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

**Giá trị trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Tham số chỉ số trên

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

**Giá trị trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```

Xác định việc căn chỉnh chỉ số phụ/chỉ số trên. Khi giá trị true, chỉ số phụ và chỉ số trên được căn chỉnh ngang với nhau. Khi giá trị false, chúng được điều chỉnh theo hình dạng của cơ sở. Giá trị mặc định là false.

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

**Giá trị trả về:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```

Xác định việc căn chỉnh chỉ số phụ/chỉ số trên. Khi giá trị true, chỉ số phụ và chỉ số trên được căn chỉnh ngang với nhau. Khi giá trị false, chúng được điều chỉnh theo hình dạng của cơ sở. Giá trị mặc định là false.

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Lấy các phần tử con

**Giá trị trả về:**
com.aspose.slides.IMathElement[]