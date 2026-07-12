---
title: MathRadical
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Especifica la función radical que consiste en una base y un grado opcional.
type: docs
url: /es/com.aspose.slides/mathradical/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

Especifica la función radical, que consiste en una base y un grado opcional. Un ejemplo de objeto radical es \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializa una nueva instancia de la clase MathRadical. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getDegree()](#getDegree--) | Argumento de grado |
| [getHideDegree()](#getHideDegree--) | Ocultar grado Cuando es true, el grado no se muestra, como en \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Ocultar grado Cuando es true, el grado no se muestra, como en \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propiedades de carácter de control |
| [getChildren()](#getChildren--) | Obtener elementos hijos |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


Inicializa una nueva instancia de la clase MathRadical.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | Grado |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argumento base

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


Argumento de grado

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


Ocultar grado Cuando es true, el grado no se muestra, como en \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Devuelve:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


Ocultar grado Cuando es true, el grado no se muestra, como en \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propiedades de carácter de control

**Devuelve:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtener elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]