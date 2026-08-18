---
title: IMathLeftSubSuperscriptElement
second_title: Aspose.Slides Java API Referenciája
description: Megadja a Sub-Superscript objektumot, amely egy alapból, egy alsó indexből és egy felső indexből áll, és az alap bal oldalára helyezkedik.
type: docs
url: /hu/com.aspose.slides/imathleftsubsuperscriptelement/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLeftSubSuperscriptElement extends IMathElement
```

Megadja a Sub-Superscript objektumot, amely egy alapból, egy alsó indexből és egy felső indexből áll, és az alap bal oldalára helyezkedik.

--------------------

> ```
> Example:
>  
>  IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").setSubSuperscriptOnTheLeft("i", "j");
>  ```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getSubscript()](#getSubscript--) | Alsó index |
| [getSuperscript()](#getSuperscript--) | Felső index |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Alap argumentum

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

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Alsó index

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

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Felső index

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

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)