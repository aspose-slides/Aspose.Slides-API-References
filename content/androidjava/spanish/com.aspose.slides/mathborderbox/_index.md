---
title: MathBorderBox
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Dibuja un borde rectangular u otro tipo de borde alrededor del IMathElement.
type: docs
url: /es/com.aspose.slides/mathborderbox/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Dibuja un borde rectangular u otro tipo de borde alrededor del IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Crea el elemento MathBorderBox con borde rectangular |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Crea el elemento MathBorderBox |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getHideTop()](#getHideTop--) | Ocultar borde superior (default is false) - especifica el estado oculto o visible del borde superior de la caja de borde. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Ocultar borde superior (default is false) - especifica el estado oculto o visible del borde superior de la caja de borde. |
| [getHideBottom()](#getHideBottom--) | Ocultar borde inferior (default is false) - especifica el estado oculto o visible del borde inferior de la caja de borde. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Ocultar borde inferior (default is false) - especifica el estado oculto o visible del borde inferior de la caja de borde. |
| [getHideLeft()](#getHideLeft--) | Ocultar borde izquierdo (default is false) - especifica el estado oculto o visible del borde izquierdo de la caja de borde. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Ocultar borde izquierdo (default is false) - especifica el estado oculto o visible del borde izquierdo de la caja de borde. |
| [getHideRight()](#getHideRight--) | Ocultar borde derecho (default is false) - especifica el estado oculto o visible del borde derecho de la caja de borde. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Ocultar borde derecho (default is false) - especifica el estado oculto o visible del borde derecho de la caja de borde. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Tachar horizontal (default is false) - especifica el estado oculto o visible de una línea horizontal tachada. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Tachar horizontal (default is false) - especifica el estado oculto o visible de una línea horizontal tachada. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Tachar vertical (default is false) - especifica el estado oculto o visible de una línea vertical tachada. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Tachar vertical (default is false) - especifica el estado oculto o visible de una línea vertical tachada. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Tachar diagonal de abajo-izquierda a arriba-derecha (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Tachar diagonal de abajo-izquierda a arriba-derecha (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Tachar diagonal de arriba-izquierda a abajo-derecha (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Tachar diagonal de arriba-izquierda a abajo-derecha (default is false). |
| [getChildren()](#getChildren--) | Obtener elementos hijos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propiedades de carácter de control |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Crea el elemento MathBorderBox con borde rectangular

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | El elemento base al que se aplica la caja de borde. Puede ser null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Crea el elemento MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | El elemento base al que se aplica la caja de borde |
| hideTop | boolean | Ocultar borde superior |
| hideBottom | boolean | Ocultar borde inferior |
| hideLeft | boolean | Ocultar borde izquierdo |
| hideRight | boolean | Ocultar borde derecho |
| strikethroughHorizontal | boolean | Tachar horizontal |
| strikethroughVertical | boolean | Tachar vertical |
| strikethroughBottomLeftToTopRight | boolean | Tachar diagonal de abajo-izquierda a arriba-derecha |
| strikethroughTopLeftToBottomRight | boolean | Tachar diagonal de arriba-izquierda a abajo-derecha |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argumento base

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

Ocultar borde superior (default is false) - especifica el estado oculto o visible del borde superior de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Devuelve:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Ocultar borde superior (default is false) - especifica el estado oculto o visible del borde superior de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Ocultar borde inferior (default is false) - especifica el estado oculto o visible del borde inferior de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Devuelve:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Ocultar borde inferior (default is false) - especifica el estado oculto o visible del borde inferior de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Ocultar borde izquierdo (default is false) - especifica el estado oculto o visible del borde izquierdo de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Devuelve:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Ocultar borde izquierdo (default is false) - especifica el estado oculto o visible del borde izquierdo de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Ocultar borde derecho (default is false) - especifica el estado oculto o visible del borde derecho de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Devuelve:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Ocultar borde derecho (default is false) - especifica el estado oculto o visible del borde derecho de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Tachar horizontal (default is false) - especifica el estado oculto o visible de una línea horizontal tachada.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Devuelve:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Tachar horizontal (default is false) - especifica el estado oculto o visible de una línea horizontal tachada.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Tachar vertical (default is false) - especifica el estado oculto o visible de una línea vertical tachada.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Devuelve:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Tachar vertical (default is false) - especifica el estado oculto o visible de una línea vertical tachada.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Tachar diagonal de abajo-izquierda a arriba-derecha (default is false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina inferior-izquierda hasta la esquina superior-derecha de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Devuelve:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Tachar diagonal de abajo-izquierda a arriba-derecha (default is false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina inferior-izquierda hasta la esquina superior-derecha de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Tachar diagonal de arriba-izquierda a abajo-derecha (default is false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina superior-izquierda hasta la esquina inferior-derecha de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Devuelve:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Tachar diagonal de arriba-izquierda a abajo-derecha (default is false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina superior-izquierda hasta la esquina inferior-derecha de la caja de borde.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtener elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propiedades de carácter de control

**Devuelve:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps