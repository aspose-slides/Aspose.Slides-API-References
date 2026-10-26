---
title: IMathBar
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يحدد دالة الشريط التي تتكون من معامل أساسي وخط فوقي أو سفلي
type: docs
url: /ar/com.aspose.slides/imathbar/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

يحدد دالة الشريط، وتتكون من معامل أساسي وخط فوقي أو سفلي

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل أساسي |
| [getPosition()](#getPosition--) | موضع خط الشريط. |
| [setPosition(int value)](#setPosition-int-) | موضع خط الشريط. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

معامل أساسي

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

موضع خط الشريط. الافتراضي: أعلى

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**القيمة المرجعة:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

موضع خط الشريط. الافتراضي: أعلى

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |