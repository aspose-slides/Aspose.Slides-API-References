---
title: ISmartArtNodeCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una raccolta di nodi SmartArt.
type: docs
url: /it/com.aspose.slides/ismartartnodecollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Rappresenta una raccolta di nodi SmartArt.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce il nodo per indice. |
| [addNode()](#addNode--) | Aggiunge un nuovo nodo o nodo secondario. |
| [removeNode(int index)](#removeNode-int-) | Rimuove il nodo o nodo secondario per indice. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Rimuove il nodo o nodo secondario. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Aggiunge un nuovo nodo nella posizione selezionata della raccolta di nodi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


Restituisce il nodo per indice. Sola lettura [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento. |

**Restituisce:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


Aggiunge un nuovo nodo o nodo secondario.

**Restituisce:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo aggiunto
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


Rimuove il nodo o nodo secondario per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice basato su zero del nodo |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


Rimuove il nodo o nodo secondario.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nodo da rimuovere. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


Aggiunge un nuovo nodo nella posizione selezionata della raccolta di nodi.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | int | Posizione del nodo basata su zero. |

**Restituisce:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo aggiunto