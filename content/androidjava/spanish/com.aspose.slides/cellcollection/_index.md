---
title: CellCollection
second_title: Referencia de la API de Aspose.Slides para Android vía Java
description: Representa una colección de celdas.
type: docs
url: /es/com.aspose.slides/cellcollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Representa una colección de celdas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Devuelve el número de celdas en una colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve una cell por su posición. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva principal de un CellCollection. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación principal de un CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```

Devuelve el número de celdas en una colección. Solo lectura int.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

Devuelve una cell por su posición. Solo lectura [Cell](../../com.aspose.slides/cell).

--------------------

Un objeto Cell puede devolverse para varios índices en caso de que la celda esté fusionada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - An java.util.Iterator for the entire collection.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva principal de un CellCollection. Solo lectura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación principal de un CellCollection. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array objetivo. |
| index | int | Índice inicial en el array objetivo. |

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