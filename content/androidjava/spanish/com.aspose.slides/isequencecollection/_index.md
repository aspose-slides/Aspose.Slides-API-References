---
title: ISequenceCollection
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa una colección de secuencias interactivas.
type: docs
url: /es/com.aspose.slides/isequencecollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Representa una colección de secuencias interactivas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Devuelve el número de elementos en una colección Solo lectura int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Agregar nueva secuencia interactiva. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Elimina la secuencia especificada de una colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina la secuencia en el índice especificado. |
| [clear()](#clear--) | Elimina todas las secuencias de una colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve una secuencia en el índice especificado. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Devuelve el número de elementos en una colección Solo lectura int.

**Devuelve:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


Agregar nueva secuencia interactiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Objeto Shape [IShape](../../com.aspose.slides/ishape) |

**Devuelve:**
[ISequence](../../com.aspose.slides/isequence) - Nueva secuencia [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


Elimina la secuencia especificada de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Secuencia a eliminar. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Elimina la secuencia en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento en la colección int |

### clear() {#clear--}
```
public abstract void clear()
```


Elimina todas las secuencias de una colección.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


Devuelve una secuencia en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento. |

**Devuelve:**
[ISequence](../../com.aspose.slides/isequence) - El objeto [ISequence](../../com.aspose.slides/isequence).