---
title: MathSuperscriptElement
second_title: Aspose.Slides para Android mediante la Referencia de API Java
description: Especifica el objeto superíndice que consiste en una base y un superíndice de tamaño reducido colocado encima y a la derecha
type: docs
url: /es/com.aspose.slides/mathsuperscriptelement/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

Especifica el objeto superíndice, que consiste en una base y un superíndice de tamaño reducido colocado encima y a la derecha

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializa una nueva instancia de la clase MathSuperscriptElement. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | Superíndice |
| [getChildren()](#getChildren--) | Obtener elementos hijos |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```


Inicializa una nueva instancia de la clase MathSuperscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Superíndice

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
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