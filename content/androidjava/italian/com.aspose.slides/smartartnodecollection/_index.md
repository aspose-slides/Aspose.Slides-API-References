---
title: SmartArtNodeCollection
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta una collezione di nodi SmartArt.
type: docs
url: /it/com.aspose.slides/smartartnodecollection/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Rappresenta una collezione di nodi SmartArt.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce il nodo per indice |
| [size()](#size--) | Restituisce il conteggio dei nodi nella collezione Sola lettura int Sola lettura int . |
| [addNode()](#addNode--) | Aggiunge un nuovo nodo SmartArt o sotto-nodo. |
| [removeNode(int index)](#removeNode-int-) | Rimuove un nodo o sotto-nodo per indice |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Rimuove un nodo o sotto-nodo |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Aggiunge un nuovo nodo nella posizione selezionata della collezione di nodi |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```


Restituisce il nodo per indice

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento |

**Restituisce:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Il nodo SmartArt
### size() {#size--}
```
public final int size()
```


Restituisce il conteggio dei nodi nella collezione Sola lettura int Sola lettura int .

**Restituisce:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```


Aggiunge un nuovo nodo SmartArt o sotto-nodo.

**Restituisce:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo aggiunto
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```


Rimuove un nodo o sotto-nodo per indice

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice basato su zero del nodo |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```


Rimuove un nodo o sotto-nodo

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nodo da rimuovere |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```


Aggiunge un nuovo nodo nella posizione selezionata della collezione di nodi

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | int | Posizione del nodo basata su zero |

**Restituisce:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nodo aggiunto
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```


Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Un java.util.Iterator per l'intera collezione.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia tutti gli elementi dalla collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). Sola lettura boolean .

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Restituisce una radice di sincronizzazione. Sola lettura Object.

**Restituisce:**
java.lang.Object