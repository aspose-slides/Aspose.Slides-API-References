---
title: MathFunction
second_title: Referencia de API Java para Aspose.Slides en Android
description: Especifica una función de un argumento.
type: docs
url: /es/com.aspose.slides/mathfunction/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

Especifica una función de un argumento.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializa una nueva instancia de la clase MathFunction. |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Inicializa una nueva instancia de la clase MathFunction. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getName()](#getName--) | Nombre de la función Por ejemplo, los nombres de funciones son sin y cos |
| [getBase()](#getBase--) | Argumento de la función |
| [getChildren()](#getChildren--) | Obtener elementos hijos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propiedades de caracteres de control |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```


Inicializa una nueva instancia de la clase MathFunction.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```


Inicializa una nueva instancia de la clase MathFunction.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```


Nombre de la función Por ejemplo, los nombres de funciones son sin y cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argumento de la función

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtener elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propiedades de caracteres de control

**Devuelve:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps