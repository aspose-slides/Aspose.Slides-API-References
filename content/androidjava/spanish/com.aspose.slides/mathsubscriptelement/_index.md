---
title: MathSubscriptElement
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Especifica el objeto subíndice que consta de una base y un subíndice de tamaño reducido colocado debajo y a la derecha.
type: docs
url: /es/com.aspose.slides/mathsubscriptelement/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Especifica el objeto subíndice, que consta de una base y un subíndice de tamaño reducido colocado abajo y a la derecha.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializa una nueva instancia de la clase MathSubscriptElement. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSubscript()](#getSubscript--) | Subíndice |
| [getChildren()](#getChildren--) | Obtener elementos hijos |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


Inicializa una nueva instancia de la clase MathSubscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtener elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]