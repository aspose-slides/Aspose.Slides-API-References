---
title: IMathFunction
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Xác định một hàm của một đối số.
type: docs
url: /vi/com.aspose.slides/imathfunction/
---
**Tất cả các giao diện đã thực thi:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Xác định một hàm của đối số.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getName()](#getName--) | Tên hàm. Ví dụ, các tên hàm là sin và cos |
| [getBase()](#getBase--) | Đối số hàm |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Tên hàm. Ví dụ, các tên hàm là sin và cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Đối số hàm

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)