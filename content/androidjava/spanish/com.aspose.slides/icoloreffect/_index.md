---
title: IColorEffect
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa un efecto de color para un comportamiento de animación.
type: docs
url: /es/com.aspose.slides/icoloreffect/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Representa un efecto de color para un comportamiento de animación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFrom()](#getFrom--) | Este valor se usa para especificar el color inicial del comportamiento. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Este valor se usa para especificar el color inicial del comportamiento. |
| [getTo()](#getTo--) | Describe el color resultante para el cambio de color de la animación. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Describe el color resultante para el cambio de color de la animación. |
| [getBy()](#getBy--) | Describe el valor de desplazamiento relativo para la animación de color. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Describe el valor de desplazamiento relativo para la animación de color. |
| [getColorSpace()](#getColorSpace--) | Representa el espacio de color del comportamiento. |
| [setColorSpace(int value)](#setColorSpace-int-) | Representa el espacio de color del comportamiento. |
| [getDirection()](#getDirection--) | Especifica la dirección en la que girar el matiz alrededor de la rueda de color. |
| [setDirection(int value)](#setDirection-int-) | Especifica la dirección en la que girar el matiz alrededor de la rueda de color. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Este valor se usa para especificar el color inicial del comportamiento. Lectura/escritura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Este valor se usa para especificar el color inicial del comportamiento. Lectura/escritura [IColorFormat](../../com.aspose.slides/icolorformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Describe el color resultante para el cambio de color de la animación. Lectura/escritura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Describe el color resultante para el cambio de color de la animación. Lectura/escritura [IColorFormat](../../com.aspose.slides/icolorformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Describe el valor de desplazamiento relativo para la animación de color. Lectura/escritura [IColorOffset](../../com.aspose.slides/icoloroffset).

**Devuelve:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Describe el valor de desplazamiento relativo para la animación de color. Lectura/escritura [IColorOffset](../../com.aspose.slides/icoloroffset).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

Representa el espacio de color del comportamiento. Lectura/escritura [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Devuelve:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

Representa el espacio de color del comportamiento. Lectura/escritura [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Especifica la dirección en la que girar el matiz alrededor de la rueda de color. Lectura/escritura [ColorDirection](../../com.aspose.slides/colordirection).

**Devuelve:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Especifica la dirección en la que girar el matiz alrededor de la rueda de color. Lectura/escritura [ColorDirection](../../com.aspose.slides/colordirection).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |