---
title: IMathRadical
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định hàm căn bậc bao gồm một cơ sở và một cấp độ tùy chọn.
type: docs
url: /vi/com.aspose.slides/imathradical/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Xác định hàm căn bậc, bao gồm một cơ sở và một cấp độ tùy chọn. Ví dụ về đối tượng căn bậc là \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radial("3"); // căn bậc ba
>  ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getDegree()](#getDegree--) | Đối số cấp độ |
| [getHideDegree()](#getHideDegree--) | Ẩn cấp độ Khi đúng, cấp độ sẽ không được hiển thị, như trong \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Ẩn cấp độ Khi đúng, cấp độ sẽ không được hiển thị, như trong \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Đối số cơ sở

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // căn bậc ba
>  IMathElement baseElem = radical.getBase();
>  ```


**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```

Đối số cấp độ

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // căn bậc ba
>  IMathElement degreeElem = radical.getDegree();
>  ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```

Ẩn cấp độ Khi đúng, cấp độ sẽ không được hiển thị, như trong \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // căn bậc ba
>  radical.setHideDegree(true);
>  ```


**Trả về:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```

Ẩn cấp độ Khi đúng, cấp độ sẽ không được hiển thị, như trong \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // căn bậc ba
>  radical.setHideDegree(true);
>  ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |