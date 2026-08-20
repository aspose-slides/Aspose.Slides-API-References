---
title: MathRightSubSuperscriptElement
second_title: Tham chiếu API Aspose.Slides cho Java
description: Chỉ định đối tượng Sub-Superscript, bao gồm một phần gốc và chỉ số dưới, chỉ số trên được đặt phía bên phải của phần gốc.
type: docs
url: /vi/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Tất cả giao diện được thực thi:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Chỉ định đối tượng Sub-Superscript, bao gồm một phần gốc và chỉ số dưới, chỉ số trên được đặt phía bên phải của phần gốc.

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

| Method | Mô tả |
| --- | --- |
| [getSubscript()](#getSubscript--) | Đối số chỉ số dưới |
| [getSuperscript()](#getSuperscript--) | Đối số chỉ số trên |
| [getAlignScripts()](#getAlignScripts--) | Chỉ định cách căn chỉnh của chỉ số dưới/đỉnh số trên. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Chỉ định cách căn chỉnh của chỉ số dưới/đỉnh số trên. |
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
public final IMathElement getSuperscript()
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
public final boolean getAlignScripts()
```


Chỉ định cách căn chỉnh của chỉ số dưới/đỉnh số trên. Khi true, chỉ số dưới và chỉ số trên được căn chỉnh theo chiều ngang với nhau. Khi false, chúng được điều chỉnh để phù hợp với hình dạng của phần gốc. Giá trị mặc định là false.

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
public final void setAlignScripts(boolean value)
```


Chỉ định cách căn chỉnh của chỉ số dưới/đỉnh số trên. Khi true, chỉ số dưới và chỉ số trên được căn chỉnh theo chiều ngang với nhau. Khi false, chúng được điều chỉnh để phù hợp với hình dạng của phần gốc. Giá trị mặc định là false.

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

**Trả về:**
com.aspose.slides.IMathElement[]