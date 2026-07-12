---
title: SequenceCollection
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa una colección de secuencias interactivas.
type: docs
url: /es/com.aspose.slides/sequencecollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Representa una colección de secuencias interactivas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Devuelve el número de elementos en una colección Solo lectura int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Agrega una nueva secuencia interactiva. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Elimina la secuencia especificada de una colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina la secuencia en el índice especificado. |
| [clear()](#clear--) | Elimina todas las secuencias de una colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve una secuencia en el índice especificado. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### getCount() {#getCount--}
```
public final int getCount()
```


Devuelve el número de elementos en una colección Solo lectura int.

**Devuelve:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


Agrega una nueva secuencia interactiva. Lectura/escritura [Sequence](../../com.aspose.slides/sequence).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Devuelve:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


Elimina la secuencia especificada de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Secuencia a eliminar. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina la secuencia en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la secuencia que debe ser eliminada. |

### clear() {#clear--}
```
public final void clear()
```


Elimina todas las secuencias de una colección.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


Devuelve una secuencia en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento. |

**Devuelve:**
[ISequence](../../com.aspose.slides/isequence) - El objeto [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - An java.util.Iterator for the entire collection.