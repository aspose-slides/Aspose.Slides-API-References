---
title: IMathLeftSubSuperscriptElement
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan objek Sub-Superscript yang terdiri dari sebuah basis dan subskrip serta superskrip yang ditempatkan di sebelah kiri basis.
type: docs
url: /id/com.aspose.slides/imathleftsubsuperscriptelement/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLeftSubSuperscriptElement extends IMathElement
```

Menentukan objek Sub-Superscript, yang terdiri dari basis dan subskrip serta superskrip yang ditempatkan di sebelah kiri basis.

--------------------

> ```
> Example:
>  
>  IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").setSubSuperscriptOnTheLeft("i", "j");
```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen basis |
| [getSubscript()](#getSubscript--) | Subskrip |
| [getSuperscript()](#getSuperscript--) | Superskrip |
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
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = leftSubSuperscript.getBase();
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
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = leftSubSuperscript.getSubscript();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Superskrip

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = leftSubSuperscript.getSuperscript();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)