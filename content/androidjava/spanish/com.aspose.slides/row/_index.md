---
title: Row
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa una fila en una tabla.
type: docs
url: /es/com.aspose.slides/row/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Todas las interfaces implementadas:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Representa una fila en una tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeight()](#getHeight--) | Devuelve la altura de una fila. |
| [getMinimalHeight()](#getMinimalHeight--) | Devuelve o establece la altura mínima posible de una fila. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Devuelve o establece la altura mínima posible de una fila. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Establece las propiedades de formato de porción definidas a todas las porciones de las celdas de la fila. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Establece las propiedades de formato de párrafo definidas a todos los párrafos de las celdas de la fila. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Establece las propiedades de formato de cuadro de texto definidas a todos los cuadros de texto de las celdas de la fila. |
| [getRowFormat()](#getRowFormat--) | Devuelve el objeto RowFormat que contiene las propiedades de formato para esta fila. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Devuelve la altura de una fila. Solo lectura double.

**Devuelve:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Devuelve o establece la altura mínima posible de una fila. Lectura/escritura double.

**Devuelve:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Devuelve o establece la altura mínima posible de una fila. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Establece las propiedades de formato de porción definidas a todas las porciones de las celdas de la fila.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | objeto IPortionFormat con las propiedades necesarias establecidas. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Establece las propiedades de formato de párrafo definidas a todos los párrafos de las celdas de la fila.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | objeto IParagraphFormat con las propiedades necesarias establecidas. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Establece las propiedades de formato de cuadro de texto definidas a todos los cuadros de texto de las celdas de la fila.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | objeto ITextFrameFormat con las propiedades necesarias establecidas. |
### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Devuelve el objeto RowFormat que contiene las propiedades de formato para esta fila. Solo lectura [IRowFormat](../../com.aspose.slides/irowformat).

**Devuelve:**
[IRowFormat](../../com.aspose.slides/irowformat)