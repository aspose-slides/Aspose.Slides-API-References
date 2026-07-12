---
title: TabCollection
second_title: Aspose.Slides Android számára a Java API hivatkozás révén
description: Tabulátorok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/tabcollection/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Tabulátorok gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben ténylegesen lévő elemek számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elemet. |
| [add(double position, int align)](#add-double-int-) | Hozzáad egy Tabulátort a gyűjteményhez. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Hozzáad egy Tabulátort a gyűjteményhez. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjteményben a megadott indexű elemet. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a két TabsEx példány egyenlő-e. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort az egész gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben ténylegesen lévő elemek számát. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

Visszaadja a megadott indexű elemet. Csak olvasható [Tab](../../com.aspose.slides/tab).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

Hozzáad egy Tabulátort a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Visszatér:**
[ITab](../../com.aspose.slides/itab) - Hozzáadott tabulátor.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

Hozzáad egy Tabulátort a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | A végére hozzáadandó Tab objektum. |

**Visszatér:**
int - A tabulátor hozzáadásának indexe.
### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes elemet a gyűjteményből.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a gyűjteményben a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó elem nulla alapú indexe. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a két TabsEx példány egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A jelenlegi TabsEx-hez összehasonlítandó TabsEx. |

**Visszatér:**
boolean - **true** ha a megadott TabsEx egyenlő a jelenlegi TabsEx-szel; egyébként **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - A IGenericEnumerator, amelyet a gyűjtemény bejárásához lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

Visszaad egy java iterátort az egész gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Egy java.util.Iterator a teljes gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

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