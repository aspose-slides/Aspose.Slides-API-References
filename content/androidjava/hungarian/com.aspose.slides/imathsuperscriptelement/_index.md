---
title: IMathSuperscriptElement
second_title: Aspose.Slides Androidhoz Java API referencia
description: Megadja a felső index objektumot, amely egy alapelemből és egy kisebb méretű felső indexből áll, amely felül és jobbra helyezkedik el
type: docs
url: /hu/com.aspose.slides/imathsuperscriptelement/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Meghatározza a felső index objektumot, amely egy alapelemből és egy kisebb méretű felső indexből áll, amely felül és jobbra helyezkedik el

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Metódusok

| Metódus | Leírás |
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