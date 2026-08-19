---
title: IMathRightSubSuperscriptElement
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan objek Sub-Superskrip yang terdiri dari basis dan subskrip serta superskrip yang ditempatkan di sebelah kanan basis.
type: docs
url: /id/com.aspose.slides/imathrightsubsuperscriptelement/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Menentukan objek Sub-Superskrip, yang terdiri dari basis dan subskrip serta superskrip yang ditempatkan di sebelah kanan basis.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen basis |
| [getSubscript()](#getSubscript--) | Argumen subskrip |
| [getSuperscript()](#getSuperscript--) | Argumen superskrip |
| [getAlignScripts()](#getAlignScripts--) | Menentukan perataan subskrip/superskrip. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Menentukan perataan subskrip/superskrip. |
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
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Argumen subskrip

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Argumen superskrip

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```


Menentukan perataan subskrip/superskrip. Ketika true, subskrip dan superskrip disejajarkan secara horizontal satu sama lain. Ketika false, mereka dikern ke bentuk basis. Nilai default adalah false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Mengembalikan:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```


Menentukan perataan subskrip/superskrip. Ketika true, subskrip dan superskrip disejajarkan secara horizontal satu sama lain. Ketika false, mereka dikern ke bentuk basis. Nilai default adalah false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |