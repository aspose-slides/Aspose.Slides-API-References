---
title: SmartArtNodeCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci uzlů SmartArt.
type: docs
url: /cs/com.aspose.slides/smartartnodecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Representuje kolekci uzlů SmartArt.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací uzel podle indexu |
| [size()](#size--) | Vrací počet uzlů v kolekci Pouze ke čtení int Pouze ke čtení int . |
| [addNode()](#addNode--) | Přidá nový uzel SmartArt nebo poduzel. |
| [removeNode(int index)](#removeNode-int-) | Odstraní uzel nebo poduzel podle indexu |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Odstraní uzel nebo poduzel |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Přidá nový uzel na vybranou pozici v kolekci uzlů |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopíruje všechny prvky z kolekce do určeného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Vrací uzel podle indexu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku |

**Návratová hodnota:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Uzlu SmartArt
### size() {#size--}
```
public final int size()
```

Vrací počet uzlů v kolekci Pouze ke čtení int Pouze ke čtení int .

**Návratová hodnota:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Přidá nový uzel SmartArt nebo poduzel.

**Návratová hodnota:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Přidaný uzel
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Odstraní uzel nebo poduzel podle indexu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index uzlu |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Odstraní uzel nebo poduzel

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Uzel k odstranění |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Přidá nový uzel na vybranou pozici v kolekci uzlů

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | int | Nulová pozice uzlu |

**Návratová hodnota:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Přidaný uzel
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - java.util.Iterator pro celou kolekci.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopíruje všechny prvky z kolekce do určeného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze ke čtení boolean .

**Návratová hodnota:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze ke čtení Object.

**Návratová hodnota:**
java.lang.Object