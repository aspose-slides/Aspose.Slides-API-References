---
title: MathBar
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Especifica la función de barra que consiste en un argumento base y una barra superior o inferior
type: docs
url: /es/com.aspose.slides/mathbar/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

Especifica la función de barra, que consiste en un argumento base y una barra superior o inferior

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | Inicializa MathBar con barra superior (posición superior) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | Inicializa MathBar con posición especificada |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getPosition()](#getPosition--) | Posición de la línea de barra. |
| [setPosition(int value)](#setPosition-int-) | Posición de la línea de barra. |
| [getChildren()](#getChildren--) | Obtiene los elementos hijos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propiedades de carácter de control |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```

Inicializa MathBar con barra superior (posición superior)

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | El elemento base al que se aplica la barra |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```

Inicializa MathBar con posición especificada

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | El elemento base al que se aplica la barra |
| position | int | Posición de la línea de barra. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argumento base

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Posición de la línea de barra. Predeterminado: Superior

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Devuelve:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Posición de la línea de barra. Predeterminado: Superior

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtiene los elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propiedades de carácter de control

**Devuelve:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps