---
title: VbaReferenceCollection
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa una colección de referencias a un proyecto VBA.
type: docs
url: /es/com.aspose.slides/vbareferencecollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
```
public class VbaReferenceCollection implements IVbaReferenceCollection
```

Representa una colección de referencias a un proyecto VBA.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | Agrega la nueva referencia a la colección de referencias |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
### size() {#size--}
```
public final int size()
```


Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int.

**Devuelve:**
int
### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public final void add(IVbaReference value)
```


Agrega la nueva referencia a la colección de referencias

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) |  |

### get_Item(int index) {#get-Item-int-}
```
public final IVbaReference get_Item(int index)
```


Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IVbaReference](../../com.aspose.slides/ivbareference)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - An java.util.Iterator for the entire collection.
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