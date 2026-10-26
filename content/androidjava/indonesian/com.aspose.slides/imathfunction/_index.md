---
title: IMathFunction
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menentukan fungsi dari sebuah argumen.
type: docs
url: /id/com.aspose.slides/imathfunction/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Menentukan fungsi dari sebuah argumen.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getName()](#getName--) | Nama fungsi Misalnya, nama fungsi adalah sin dan cos |
| [getBase()](#getBase--) | Argumen Fungsi |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Nama fungsi Misalnya, nama fungsi adalah sin dan cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
>  ```


**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumen Fungsi

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)