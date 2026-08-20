---
title: MathSuperscriptElement
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định đối tượng chỉ số trên, bao gồm một cơ sở và một chỉ số trên có kích thước giảm đặt ở phía trên và bên phải
type: docs
url: /vi/com.aspose.slides/mathsuperscriptelement/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

Xác định đối tượng chỉ số trên, bao gồm một cơ sở và một chỉ số trên có kích thước giảm đặt ở phía trên và bên phải

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Khởi tạo một thể hiện mới của lớp MathSuperscriptElement. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | Chỉ số trên |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
### MathSuperscriptElement(IMMathElement baseArg, IMMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```


Khởi tạo một thể hiện mới của lớp MathSuperscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Chỉ số trên

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
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