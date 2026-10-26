---
title: SequenceCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una colección de secuencias interactivas.
type: docs
url: /es/com.aspose.slides/sequencecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
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
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Secuencia a eliminar. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina la secuencia en el índice especificado.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice de una secuencia que debe eliminarse. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice del elemento. |

**Devuelve:**
[ISequence](../../com.aspose.slides/isequence) - El objeto [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Un IGenericEnumerator que puede usarse para recorrer la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Un java.util.Iterator para toda la colección.