---
title: IMathSuperscriptElement
second_title: Aspose.Slides para Android vía referencia de API Java
description: Especifica el objeto superíndice que consiste en una base y un superíndice de tamaño reducido colocado encima y a la derecha
type: docs
url: /es/com.aspose.slides/imathsuperscriptelement/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Especifica el objeto superíndice, que consiste en una base y un superíndice de tamaño reducido colocado encima y a la derecha

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
```
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getSuperscript()](#getSuperscript--) | Superíndice |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumento base

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Superíndice

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)