---
title: IMathBar
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định hàm bar, bao gồm một đối số cơ bản và một overbar hoặc underbar
type: docs
url: /vi/com.aspose.slides/imathbar/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Xác định hàm bar, bao gồm một đối số cơ bản và một overbar hoặc underbar

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Phương thức

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ bản |
| [getPosition()](#getPosition--) | Vị trí của đường gạch. |
| [setPosition(int value)](#setPosition-int-) | Vị trí của đường gạch. |
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


Vị trí của đường gạch. Mặc định: Top

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


Vị trí của đường gạch. Mặc định: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |