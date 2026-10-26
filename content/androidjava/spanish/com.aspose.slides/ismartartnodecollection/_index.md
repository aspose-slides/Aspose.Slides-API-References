---
title: ISmartArtNodeCollection
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa una colección de nodos SmartArt.
type: docs
url: /es/com.aspose.slides/ismartartnodecollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Representa una colección de nodos SmartArt.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve el nodo por índice. |
| [addNode()](#addNode--) | Agregar nuevo nodo o subnodo. |
| [removeNode(int index)](#removeNode-int-) | Eliminar nodo o subnodo por índice. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Eliminar nodo o subnodo. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Agregar nuevo nodo en la posición seleccionada de la colección de nodos. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

Devuelve el nodo por índice. Solo lectura [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento. |

**Devuelve:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

Agregar nuevo nodo o subnodo.

**Devuelve:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo agregado
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

Eliminar nodo o subnodo por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice basado en cero del nodo |
### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

Eliminar nodo o subnodo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nodo a eliminar. |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

Agregar nuevo nodo en la posición seleccionada de la colección de nodos.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | int | Posición del nodo basada en cero. |

**Devuelve:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo agregado