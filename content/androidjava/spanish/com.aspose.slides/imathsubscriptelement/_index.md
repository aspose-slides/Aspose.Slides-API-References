---
title: IMathSubscriptElement
second_title: Aspose.Slides para Android a través de la Referencia de API Java
description: Especifica el objeto subíndice que consiste en una base y un subíndice de tamaño reducido colocado debajo y a la derecha.
type: docs
url: /es/com.aspose.slides/imathsubscriptelement/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Especifica el objeto subíndice, que consiste en una base y un subíndice de tamaño reducido colocado debajo y a la derecha.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getSubscript()](#getSubscript--) | Subíndice |
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
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
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
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```


**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)