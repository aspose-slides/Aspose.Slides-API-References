---
title: ICellFormat
second_title: Aspose.Slides para Android a través de la referencia API de Java
description: Representa el formato de una celda de tabla.
type: docs
url: /es/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Representa el formato de una celda de tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Devuelve un objeto de propiedades de relleno de celda. |
| [getBorderLeft()](#getBorderLeft--) | Devuelve un objeto de propiedades de línea del borde izquierdo. |
| [getBorderTop()](#getBorderTop--) | Devuelve un objeto de propiedades de línea del borde superior. |
| [getBorderRight()](#getBorderRight--) | Devuelve un objeto de propiedades de línea del borde derecho. |
| [getBorderBottom()](#getBorderBottom--) | Devuelve un objeto de propiedades de línea del borde inferior. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Devuelve un objeto de propiedades de línea diagonal de arriba-izquierda a abajo-derecha. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Devuelve un objeto de propiedades de línea diagonal de abajo-izquierda a arriba-derecha. |
| [getTransparency()](#getTransparency--) | Obtiene o establece la transparencia del color de relleno. |
| [setTransparency(float value)](#setTransparency-float-) | Obtiene o establece la transparencia del color de relleno. |
| [getEffective()](#getEffective--) | Obtiene las propiedades de formato efectivas de la celda de tabla con herencia y estilos de tabla aplicados. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Devuelve un objeto de propiedades de relleno de celda. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

Devuelve un objeto de propiedades de línea del borde izquierdo. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

Devuelve un objeto de propiedades de línea del borde superior. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

Devuelve un objeto de propiedades de línea del borde derecho. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

Devuelve un objeto de propiedades de línea del borde inferior. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

Devuelve un objeto de propiedades de línea diagonal de arriba-izquierda a abajo-derecha. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

Devuelve un objeto de propiedades de línea diagonal de abajo-izquierda a arriba-derecha. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Obtiene o establece la transparencia del color de relleno. Lectura/escritura  float .

**Devuelve:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Obtiene o establece la transparencia del color de relleno. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

Obtiene las propiedades de formato efectivas de la celda de tabla con herencia y estilos de tabla aplicados.

**Devuelve:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Un [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).