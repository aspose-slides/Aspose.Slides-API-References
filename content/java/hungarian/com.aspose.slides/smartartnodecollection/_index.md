---
title: SmartArtNodeCollection
second_title: Aspose.Slides for Java API Referencia
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

Egy SmartArt csomópontok gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A csomópontot index alapján adja vissza |
| [size()](#size--) | Visszaadja a gyűjtemény csomópontjainak számát Csak olvasható int Csak olvasható int. |
| [addNode()](#addNode--) | Új SmartArt csomópontot vagy alcsomópontot ad hozzá. |
| [removeNode(int index)](#removeNode-int-) | Csomópont vagy alcsomópont eltávolítása index alapján |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Csomópont vagy alcsomópont eltávolítása |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Új csomópont hozzáadása a csomópontok gyűjteményének kiválasztott pozíciójába |
| [iterator()](#iterator--) | Visszaad egy felsorolót, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Az összes elemet átmásolja a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |

### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

A csomópontot index alapján adja vissza

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

Visszaadja a gyűjtemény csomópontjainak számát Csak olvasható int Csak olvasható int.

**Visszatérési érték:**
int

### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Új SmartArt csomópontot vagy alcsomópontot ad hozzá.

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
| index | int | A csomópont nulla-alapú indexe |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Csomópont vagy alcsomópont eltávolítása

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Az eltávolítandó csomópont |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Új csomópont hozzáadása a csomópontok gyűjteményének kiválasztott pozíciójába

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | int | A csomópont nulla-alapú pozíciója |

**Visszatérési érték:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Hozzáadott csomópont

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Visszaad egy felsorolót, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - A IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.

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

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható boolean .

**Visszatérési érték:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object