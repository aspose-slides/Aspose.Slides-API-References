---
title: MathRadical
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Chỉ định hàm căn bậc bao gồm một cơ sở và một bậc tùy chọn.
type: docs
url: /vi/com.aspose.slides/mathradical/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

Chỉ định hàm căn bậc, gồm một cơ sở và một bậc tùy chọn. Ví dụ của đối tượng căn bậc là \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## Hàm tạo

| Constructor | Description |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Khởi tạo một thể hiện mới của lớp MathRadical. |
## Phương thức

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getDegree()](#getDegree--) | Đối số bậc |
| [getHideDegree()](#getHideDegree--) | Ẩn bậc Khi là true, bậc sẽ không được hiển thị, như trong \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Ẩn bậc Khi là true, bậc sẽ không được hiển thị, như trong \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Thuộc tính ký tự điều khiển |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


Khởi tạo một thể hiện mới của lớp MathRadical.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Cơ sở |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | Bậc |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Đối số cơ sở

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


Đối số bậc

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


Ẩn bậc Khi là true, bậc sẽ không được hiển thị, như trong \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Trả về:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


Ẩn bậc Khi là true, bậc sẽ không được hiển thị, như trong \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Thuộc tính ký tự điều khiển

**Trả về:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Lấy các phần tử con

**Trả về:**
com.aspose.slides.IMathElement[]