---
title: CellCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A cellák gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/cellcollection/
---
**Öröklés:**
java.lang.Object

**Összes implementált interfész:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

A cellák gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Visszaadja a cellák számát a gyűjteményben. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy cellát a pozíciója alapján. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [getSlide()](#getSlide--) | Visszaadja a CellCollection szülő diát. |
| [getPresentation()](#getPresentation--) | Visszaadja a CellCollection szülő prezentációját. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja az összes elemet a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```

Visszaadja a cellák számát a gyűjteményben. Csak olvasható int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

Visszaad egy cellát a pozíciója alapján. Csak olvasható [Cell](../../com.aspose.slides/cell).

--------------------

Egy Cell objektum több index esetén is visszaadható, ha a cella össze van vonva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Egy IGenericEnumerator, amelyet a gyűjtemény bejárására lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Egy java.util.Iterator a teljes gyűjteményhez.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a CellCollection szülő diát. Csak olvasható [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a CellCollection szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja az összes elemet a gyűjteményből a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatér:**
java.lang.Object