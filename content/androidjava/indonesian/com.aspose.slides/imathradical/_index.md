---
title: IMathRadical
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menentukan fungsi radikal yang terdiri dari basis dan derajat opsional.
type: docs
url: /id/com.aspose.slides/imathradical/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Menentukan fungsi radikal, yang terdiri dari basis, dan derajat opsional. Contoh objek radikal adalah \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // akar kubik
>  ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen basis |
| [getDegree()](#getDegree--) | Argumen derajat |
| [getHideDegree()](#getHideDegree--) | Sembunyikan derajat. Ketika true, derajat tidak ditampilkan, seperti pada \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Sembunyikan derajat. Ketika true, derajat tidak ditampilkan, seperti pada \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumen basis

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  IMathElement baseElem = radical.getBase();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Argumen derajat

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // akar kubik
>  IMathElement degreeElem = radical.getDegree();
>  ```


**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Sembunyikan derajat. Ketika true, derajat tidak ditampilkan, seperti pada \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // akar kubik
>  radical.setHideDegree(true);
>  ```


**Mengembalikan:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Sembunyikan derajat. Ketika true, derajat tidak ditampilkan, seperti pada \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // akar kubik
>  radical.setHideDegree(true);
>  ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |