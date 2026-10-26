---
title: ISmartArtNodeCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una collezione di nodi SmartArt.
type: docs
url: /it/com.aspose.slides/ismartartnodecollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Rappresenta una collezione di nodi SmartArt.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce il nodo per indice. |
| [addNode()](#addNode--) | Aggiunge un nuovo nodo o sotto-nodo. |
| [removeNode(int index)](#removeNode-int-) | Rimuove il nodo o sotto-nodo per indice. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Rimuove il nodo o sotto-nodo. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Aggiunge un nuovo nodo nella posizione selezionata della collezione di nodi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


Restituisce il nodo per indice. Solo lettura [ISmartArtNode](../../com.aspose.slides/ismartartnode)

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


Aggiunge un nuovo nodo o sotto-nodo.

**Restituisce:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo aggiunto
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


Rimuove il nodo o sotto-nodo per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice basato su zero del nodo |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


Rimuove il nodo o sotto-nodo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nodo da rimuovere. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


Aggiunge un nuovo nodo nella posizione selezionata della collezione di nodi.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | int | Posizione del nodo basata su zero. |

**Restituisce:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo aggiunto