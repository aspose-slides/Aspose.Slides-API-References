---
title: CellCollection
second_title: Aspose.Slides pro Android přes Java API referenci
description: Představuje kolekci buněk.
type: docs
url: /cs/com.aspose.slides/cellcollection/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Představuje kolekci buněk.
## Metody

| Metoda | Popis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Vrací počet buněk ve sbírce. |
| [get_Item(int index)](#get-Item-int-) | Vrací buňku podle její pozice. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází sbírkou. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterator pro celou sbírku. |
| [getSlide()](#getSlide--) | Vrací nadřazený slide kolekce CellCollection. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou presentation kolekce CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky ze sbírky do určeného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu, která určuje, zda je přístup ke sbírce synchronizovaný (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```

Vrací počet buněk ve sbírce. Pouze pro čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

Vrací buňku podle její pozice. Pouze pro čtení [Cell](../../com.aspose.slides/cell).

--------------------

Objekt One Cell může být vrácen pro několik indexů v případě, že je buňka sloučena.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

Vrací enumerátor, který prochází sbírkou.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - IGenericEnumerator, který lze použít k iteraci přes sbírku.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

Vrací java iterator pro celou sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - java.util.Iterator pro celou sbírku.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený slide kolekce CellCollection. Pouze pro čtení [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou presentation kolekce CellCollection. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky ze sbírky do určeného pole.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int |  |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu, která určuje, zda je přístup ke sbírce synchronizovaný (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object