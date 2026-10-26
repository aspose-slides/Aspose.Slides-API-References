---
title: RowCollection
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa la colección de filas de tabla.
type: docs
url: /es/com.aspose.slides/rowcollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Representa la colección de filas de tabla.

## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Obtiene el número de filas realmente contenidas en la colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve la fila en el índice especificado. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Crea una copia de la fila de plantilla especificada y la inserta en la posición especificada de una tabla. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Elimina una fila en la posición especificada de una tabla. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |

### size() {#size--}
```
public final int size()
```

Obtiene el número de filas realmente contenidas en la colección. Solo lectura int.

**Devuelve:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

Devuelve la fila en el índice especificado. Solo lectura [Row](../../com.aspose.slides/row).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IRow](../../com.aspose.slides/irow)

### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Fila que se usa como plantilla. |
| withAttachedRows | boolean | Verdadero para copiar también todas las filas adjuntas a la fila plantilla. |

**Devuelve:**
com.aspose.slides.IRow[] - Filas añadidas.

### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Crea una copia de la fila de plantilla especificada y la inserta en la posición especificada de una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la nueva fila. |
| templ | [IRow](../../com.aspose.slides/irow) | Fila que se usa como plantilla. |
| withAttachedRows | boolean | Verdadero para copiar también todas las filas adjuntas a la fila plantilla. |

**Devuelve:**
com.aspose.slides.IRow[] - Filas insertadas.

### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Elimina una fila en la posición especificada de una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstRowIndex | int | Índice de la fila a eliminar. |
| withAttachedRows | boolean | Verdadero para eliminar también todas las filas adjuntas. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Un IGenericEnumerator que puede usarse para recorrer la colección.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Un java.util.Iterator para toda la colección.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial en el array de destino. |

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