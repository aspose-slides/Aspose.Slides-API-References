---
title: IMathLeftSubSuperscriptElement
second_title: Aspose.Slides para Android a través de la referencia de API de Java
description: Especifica el objeto Sub-Superíndice que consta de una base y un subíndice y superíndice colocados a la izquierda de la base.
type: docs
url: /es/com.aspose.slides/imathleftsubsuperscriptelement/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLeftSubSuperscriptElement extends IMathElement
```

Especifica el objeto Sub-Superíndice, que consta de una base y un subíndice y superíndice colocados a la izquierda de la base.

--------------------

> ```
> Example:
>  
>  IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").setSubSuperscriptOnTheLeft("i", "j");
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getSubscript()](#getSubscript--) | Subíndice |
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
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = leftSubSuperscript.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Subíndice

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
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = leftSubSuperscript.getSuperscript();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)