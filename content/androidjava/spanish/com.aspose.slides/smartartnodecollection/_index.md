---
title: SmartArtNodeCollection
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa una colección de nodos SmartArt.
type: docs
url: /es/com.aspose.slides/smartartnodecollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Representa una colección de nodos SmartArt.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve el nodo por índice |
| [size()](#size--) | Devuelve el recuento de nodos en la colección Solo lectura  int  Solo lectura  int . |
| [addNode()](#addNode--) | Agregar nuevo nodo SmartArt o subnodo. |
| [removeNode(int index)](#removeNode-int-) | Eliminar nodo o subnodo por índice |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Eliminar nodo o subnodo |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Agregar nuevo nodo en la posición seleccionada de la colección de nodos |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```


Devuelve el nodo por índice

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento |

**Devuelve:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - El nodo SmartArt
### size() {#size--}
```
public final int size()
```


Devuelve el recuento de nodos en la colección Solo lectura  int  Solo lectura  int .

**Devuelve:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```


Agregar nuevo nodo SmartArt o subnodo.

**Devuelve:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo agregado
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```


Eliminar nodo o subnodo por índice

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice basado en cero del nodo |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```


Eliminar nodo o subnodo

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nodo a eliminar |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```


Agregar nuevo nodo en la posición seleccionada de la colección de nodos

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | int | Posición del nodo basada en cero |

**Devuelve:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo agregado
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Un IGenericEnumerator que puede usarse para recorrer la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Un java.util.Iterator para toda la colección.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array destino. |
| index | int | Índice de inicio en el array destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). Solo lectura  boolean .

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Devuelve una raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object