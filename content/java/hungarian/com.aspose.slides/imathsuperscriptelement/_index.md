---
title: IMathSuperscriptElement
second_title: Aspose.Slides Java API Referencia
description: Megadja a felső index objektumot, amely egy alapból és egy kisebb méretű felső indexből áll, felül és jobbra helyezkedik el
type: docs
url: /hu/com.aspose.slides/imathsuperscriptelement/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Meghatározza a felső index objektumot, amely egy alapból és egy kisebb méretű, jobbra felül elhelyezett felső indexből áll

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Módszerek

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
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
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
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
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```


**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)