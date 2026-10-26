---
title: IMathSubscriptElement
second_title: Aspose.Slides untuk Referensi API Java
description: Menentukan objek subskrip yang terdiri dari basis dan subskrip berukuran kecil yang ditempatkan di bawah dan di kanan.
type: docs
url: /id/com.aspose.slides/imathsubscriptelement/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Menentukan objek subskrip, yang terdiri dari basis dan subskrip ukuran kecil yang ditempatkan di bawah dan di kanan.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen basis |
| [getSubscript()](#getSubscript--) | Subskrip |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumen basis

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```


**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Subskrip

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```


**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)