---
title: IMathBar
second_title: Aspose.Slides için Java API Referansı
description: Temel argüman ve üst çubuk veya alt çubuk içeren bar işlevini belirtir
type: docs
url: /tr/com.aspose.slides/imathbar/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Bar işlevini tanımlar; bir temel argüman ve bir üst çubuk veya alt çubuk içerir

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  ```
## Yöntemler

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getPosition()](#getPosition--) | Bar çizgisinin konumu. |
| [setPosition(int value)](#setPosition-int-) | Bar çizgisinin konumu. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Temel argüman

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Bar çizgisinin konumu. Varsayılan: Üst

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
>  ```

**Döndürür:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Bar çizgisinin konumu. Varsayılan: Üst

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
>  ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |