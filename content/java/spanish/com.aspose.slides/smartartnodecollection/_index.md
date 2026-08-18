---
title: SmartArtNodeCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una colección de nodos SmartArt.
type: docs
url: /es/com.aspose.slides/smartartnodecollection/
---
**Herencia:**
java.lang.Object

**Todas las Interfaces Implementadas:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Representa una colección de nodos SmartArt.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve el nodo por índice |
| [size()](#size--) | Devuelve el recuento de nodos en la colección Solo lectura int Solo lectura int. |
| [addNode()](#addNode--) | Añade un nuevo nodo SmartArt o subnodo. |
| [removeNode(int index)](#removeNode-int-) | Elimina nodo o subnodo por índice |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Elimina nodo o subnodo |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Añade un nuevo nodo en la posición seleccionada de la colección de nodos |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para hilos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Devuelve el nodo por índice

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice base cero del elemento |

**Devuelve:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - El nodo SmartArt
### size() {#size--}
```
public final int size()
```

Devuelve el recuento de nodos en la colección Solo lectura int Solo lectura int.

**Devuelve:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Añade un nuevo nodo SmartArt o subnodo.

**Devuelve:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo añadido
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Elimina nodo o subnodo por índice

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice base cero del nodo |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Elimina nodo o subnodo

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nodo a eliminar |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Añade un nuevo nodo en la posición seleccionada de la colección de nodos

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | int | Posición del nodo base cero |

**Devuelve:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo añadido
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - An java.util.Iterator for the entire collection.
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

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para hilos). Solo lectura boolean.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object