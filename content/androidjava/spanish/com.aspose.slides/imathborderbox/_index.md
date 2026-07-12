---
title: IMathBorderBox
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Dibuja un borde rectangular u otro alrededor del IMathElement.
type: docs
url: /es/com.aspose.slides/imathborderbox/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Dibuja un borde rectangular u otro alrededor del IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getHideTop()](#getHideTop--) | Ocultar borde superior (valor predeterminado es false) - especifica el estado oculto o visible del borde superior del cuadro de borde. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Ocultar borde superior (valor predeterminado es false) - especifica el estado oculto o visible del borde superior del cuadro de borde. |
| [getHideBottom()](#getHideBottom--) | Ocultar borde inferior (valor predeterminado es false) - especifica el estado oculto o visible del borde inferior del cuadro de borde. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Ocultar borde inferior (valor predeterminado es false) - especifica el estado oculto o visible del borde inferior del cuadro de borde. |
| [getHideLeft()](#getHideLeft--) | Ocultar borde izquierdo (valor predeterminado es false) - especifica el estado oculto o visible del borde izquierdo del cuadro de borde. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Ocultar borde izquierdo (valor predeterminado es false) - especifica el estado oculto o visible del borde izquierdo del cuadro de borde. |
| [getHideRight()](#getHideRight--) | Ocultar borde derecho (valor predeterminado es false) - especifica el estado oculto o visible del borde derecho del cuadro de borde. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Ocultar borde derecho (valor predeterminado es false) - especifica el estado oculto o visible del borde derecho del cuadro de borde. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Tachado horizontal (valor predeterminado es false) - especifica el estado oculto o visible de una línea horizontal tachada. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Tachado horizontal (valor predeterminado es false) - especifica el estado oculto o visible de una línea horizontal tachada. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Tachado vertical (valor predeterminado es false) - especifica el estado oculto o visible de una línea vertical tachada. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Tachado vertical (valor predeterminado es false) - especifica el estado oculto o visible de una línea vertical tachada. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Tachado de esquina inferior izquierda a esquina superior derecha (valor predeterminado es false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Tachado de esquina inferior izquierda a esquina superior derecha (valor predeterminado es false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Tachado de esquina superior izquierda a esquina inferior derecha (valor predeterminado es false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Tachado de esquina superior izquierda a esquina inferior derecha (valor predeterminado es false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumento base

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```


**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

Ocultar borde superior (valor predeterminado es false) - especifica el estado oculto o visible del borde superior del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Devuelve:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

Ocultar borde superior (valor predeterminado es false) - especifica el estado oculto o visible del borde superior del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

Ocultar borde inferior (valor predeterminado es false) - especifica el estado oculto o visible del borde inferior del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Devuelve:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

Ocultar borde inferior (valor predeterminado es false) - especifica el estado oculto o visible del borde inferior del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

Ocultar borde izquierdo (valor predeterminado es false) - especifica el estado oculto o visible del borde izquierdo del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Devuelve:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

Ocultar borde izquierdo (valor predeterminado es false) - especifica el estado oculto o visible del borde izquierdo del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

Ocultar borde derecho (valor predeterminado es false) - especifica el estado oculto o visible del borde derecho del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```


**Devuelve:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

Ocultar borde derecho (valor predeterminado es false) - especifica el estado oculto o visible del borde derecho del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

Tachado horizontal (valor predeterminado es false) - especifica el estado oculto o visible de una línea horizontal tachada.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Devuelve:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

Tachado horizontal (valor predeterminado es false) - especifica el estado oculto o visible de una línea horizontal tachada.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

Tachado vertical (valor predeterminado es false) - especifica el estado oculto o visible de una línea vertical tachada.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Devuelve:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

Tachado vertical (valor predeterminado es false) - especifica el estado oculto o visible de una línea vertical tachada.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

Tachado de esquina inferior izquierda a esquina superior derecha (valor predeterminado es false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina inferior izquierda hasta la esquina superior derecha del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Devuelve:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

Tachado de esquina inferior izquierda a esquina superior derecha (valor predeterminado es false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina inferior izquierda hasta la esquina superior derecha del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

Tachado de esquina superior izquierda a esquina inferior derecha (valor predeterminado es false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina superior izquierda hasta la esquina inferior derecha del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Devuelve:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

Tachado de esquina superior izquierda a esquina inferior derecha (valor predeterminado es false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina superior izquierda hasta la esquina inferior derecha del cuadro de borde.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |