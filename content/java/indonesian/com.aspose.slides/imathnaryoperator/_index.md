---
title: IMathNaryOperator
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan objek matematika N-ary seperti Summation dan Integral.
type: docs
url: /id/com.aspose.slides/imathnaryoperator/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Menentukan objek matematika N-ary, seperti Summation dan Integral. Objek ini terdiri dari operator, basis (atau operand), dan batas atas serta bawah opsional. Contoh operator N-ary meliputi: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen basis |
| [getSubscript()](#getSubscript--) | Menentukan argumen subskrip yang, misalnya, dalam kasus integral, menetapkan batas bawah |
| [getSuperscript()](#getSuperscript--) | Menentukan argumen supersript yang, misalnya, dalam kasus integral, menetapkan batas atas |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumen basis

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Menentukan argumen subskrip yang, misalnya, dalam kasus integral, menetapkan batas bawah

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Menentukan argumen supersript yang, misalnya, dalam kasus integral, menetapkan batas atas

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)