---
title: IRow
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa una fila en una tabla.
type: docs
url: /es/com.aspose.slides/irow/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Representa una fila en una tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeight()](#getHeight--) | Devuelve la altura de una fila. |
| [getMinimalHeight()](#getMinimalHeight--) | Devuelve o establece la altura mínima posible de una fila. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Devuelve o establece la altura mínima posible de una fila. |
| [getRowFormat()](#getRowFormat--) | Devuelve el objeto RowFormat que contiene las propiedades de formato para esta fila. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Devuelve la altura de una fila. Solo lectura double.

**Devuelve:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Devuelve o establece la altura mínima posible de una fila. Lectura/escritura double.

**Devuelve:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


Devuelve o establece la altura mínima posible de una fila. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


Devuelve el objeto RowFormat que contiene las propiedades de formato para esta fila. Solo lectura [IRowFormat](../../com.aspose.slides/irowformat).

**Devuelve:**
[IRowFormat](../../com.aspose.slides/irowformat)