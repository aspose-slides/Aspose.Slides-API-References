---
title: ColumnCollection
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa una colección de columnas en una tabla.
type: docs
url: /es/com.aspose.slides/columncollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las Interfaces Implementadas:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Representa una colección de columnas en una tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve el número de columnas en una colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve la columna en el índice especificado. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Crea una copia de la columna de plantilla especificada y la inserta en la posición especificada de una tabla. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Elimina una columna en la posición especificada de una tabla. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
### size() {#size--}
```
public final int size()
```

Devuelve el número de columnas en una colección. Solo lectura int.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

Devuelve la columna en el índice especificado. Solo lectura [Column](../../com.aspose.slides/column).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Columna que se usa como plantilla. |
| withAttachedColumns | boolean | True para copiar también todas las columnas adjuntas a la fila de plantilla. |

**Devuelve:**
com.aspose.slides.IColumn[] - Columnas agregadas.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Crea una copia de la columna de plantilla especificada y la inserta en la posición especificada de una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de una nueva columna. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Columna que se usa como plantilla. |
| withAttachedColumns | boolean | True para copiar también todas las columnas adjuntas a la columna de plantilla. |

**Devuelve:**
com.aspose.slides.IColumn[] - Columnas insertadas.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Elimina una columna en la posición especificada de una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstColumnIndex | int | Índice de una columna a eliminar. |
| withAttachedRows | boolean | True para eliminar también todas las columnas adjuntas. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Un IGenericEnumerator que puede usarse para recorrer la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Un java.util.Iterator para toda la colección.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array destino. |
| index | int | Índice inicial en el array destino. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). Solo lectura boolean.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object