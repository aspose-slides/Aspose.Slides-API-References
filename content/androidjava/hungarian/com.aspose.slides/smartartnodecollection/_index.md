---
title: SmartArtNodeCollection
second_title: Aspose.Slides Androidra vonatkozó Java API hivatkozás
description: A SmartArt csomópontok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/smartartnodecollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

A SmartArt csomópontok gyűjteményét képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a csomópontot az index alapján |
| [size()](#size--) | Visszaadja a gyűjteményben lévő csomópontok számát Csak olvasható  int  Csak olvasható  int. |
| [addNode()](#addNode--) | Új SmartArt csomópont vagy alcsomópont hozzáadása. |
| [removeNode(int index)](#removeNode-int-) | Csomópont vagy alcsomópont eltávolítása index alapján |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Csomópont vagy alcsomópont eltávolítása |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Új csomópont hozzáadása a csomópontgyűjtemény kiválasztott pozíciójába |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Az összes elemet átmásolja a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |

### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Visszaadja a csomópontot az index alapján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem nulla-alapú indexe |

**Visszatérési érték:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - A SmartArt csomópont

### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben lévő csomópontok számát Csak olvasható  int  Csak olvasható  int.

**Visszatérési érték:**
int

### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Új SmartArt csomópont vagy alcsomópont hozzáadása.

**Visszatérési érték:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Hozzáadott csomópont

### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Csomópont vagy alcsomópont eltávolítása index alapján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Nulla-alapú index a csomópontnál |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Csomópont vagy alcsomópont eltávolítása

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Eltávolítandó csomópont |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Új csomópont hozzáadása a csomópontgyűjtemény kiválasztott pozíciójába

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | int | Nulla-alapú csomópont pozíció |

**Visszatérési érték:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Hozzáadott csomópont

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Egy java.util.Iterator a teljes gyűjteményhez.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Az összes elemet átmásolja a gyűjteményből a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható  boolean.

**Visszatérési érték:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object