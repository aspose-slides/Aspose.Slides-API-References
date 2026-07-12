---
title: Column
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa una columna en una tabla.
type: docs
url: /es/com.aspose.slides/column/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Todas las Interfaces Implementadas:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Representa una columna en una tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Devuelve o establece el ancho de una columna. |
| [setWidth(double value)](#setWidth-double-) | Devuelve o establece el ancho de una columna. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Establece las propiedades de formato de porción definidas en todas las porciones de las celdas de la columna. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Establece las propiedades de formato de párrafo definidas en todos los párrafos de las celdas de la columna. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Establece las propiedades de formato de marco de texto definidas en todos los marcos de texto de las celdas de la columna. |
| [getColumnFormat()](#getColumnFormat--) | Devuelve el objeto ColumnFormat que contiene las propiedades de formato para esta columna. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Devuelve o establece el ancho de una columna. Lectura/escritura double.

**Devuelve:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Devuelve o establece el ancho de una columna. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Establece las propiedades de formato de porción definidas en todas las porciones de las celdas de la columna.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | objeto IPortionFormat con las propiedades necesarias establecidas. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Establece las propiedades de formato de párrafo definidas en todos los párrafos de las celdas de la columna.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | objeto IParagraphFormat con las propiedades necesarias establecidas. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Establece las propiedades de formato de marco de texto definidas en todos los marcos de texto de las celdas de la columna.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | objeto ITextFrameFormat con las propiedades necesarias establecidas. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


Devuelve el objeto ColumnFormat que contiene las propiedades de formato para esta columna. Solo lectura [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Devuelve:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)