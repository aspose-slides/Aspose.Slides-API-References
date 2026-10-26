---
title: IMathBar
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định hàm bar, bao gồm một đối số cơ bản và một thanh trên hoặc thanh dưới
type: docs
url: /vi/com.aspose.slides/imathbar/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Xác định hàm bar, bao gồm một đối số cơ bản và một thanh trên hoặc thanh dưới

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ bản |
| [getPosition()](#getPosition--) | Vị trí của đường thanh. |
| [setPosition(int value)](#setPosition-int-) | Vị trí của đường thanh. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Đối số cơ bản

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Vị trí của đường thanh. Default: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Trả về:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Vị trí của đường thanh. Default: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |