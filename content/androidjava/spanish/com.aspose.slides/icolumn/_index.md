---
title: IColumn
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa una columna en una tabla.
type: docs
url: /es/com.aspose.slides/icolumn/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Representa una columna en una tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Devuelve o establece el ancho de una columna. |
| [setWidth(double value)](#setWidth-double-) | Devuelve o establece el ancho de una columna. |
| [getColumnFormat()](#getColumnFormat--) | Devuelve el objeto ColumnFormat que contiene las propiedades de formato para esta columna. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Devuelve o establece el ancho de una columna. Lectura/escritura double.

**Devuelve:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Devuelve o establece el ancho de una columna. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

Devuelve el objeto ColumnFormat que contiene las propiedades de formato para esta columna. Solo lectura [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Devuelve:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)