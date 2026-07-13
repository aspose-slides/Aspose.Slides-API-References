---
title: IMathBar
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menentukan fungsi bar yang terdiri dari argumen dasar dan overbar atau underbar
type: docs
url: /id/com.aspose.slides/imathbar/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Menentukan fungsi bar, terdiri dari argumen dasar dan overbar atau underbar

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen dasar |
| [getPosition()](#getPosition--) | Posisi garis bar. |
| [setPosition(int value)](#setPosition-int-) | Posisi garis bar. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumen dasar

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Posisi garis bar. Default: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Mengembalikan:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Posisi garis bar. Default: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |