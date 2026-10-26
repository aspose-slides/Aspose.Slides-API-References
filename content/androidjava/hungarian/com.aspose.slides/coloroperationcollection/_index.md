---
title: ColorOperationCollection
second_title: Aspose.Slides Androidhoz a Java API hivatkozás
description: A színtranszformációs műveletek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/coloroperationcollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

A színtranszformációs műveletek gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben lévő műveletek számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja vagy beállítja a megadott indexű műveletet. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Visszaadja vagy beállítja a megadott indexű műveletet. |
| [add(int operation, float parameter)](#add-int-float-) | Új műveletet ad a gyűjtemény végéhez. |
| [add(int operation)](#add-int-) | Új műveletet ad a gyűjtemény végéhez. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Beszúrja az új műveletet a gyűjteménybe. |
| [insert(int position, int operation)](#insert-int-int-) | Beszúrja az új műveletet a gyűjteménybe. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a színműveletet a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes színműveletet. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérobjektumot. |
| [deepClone()](#deepClone--) | Létrehoz egy másolatot a ColorOperationCollection gyűjteményről. |
| [cloneT()](#cloneT--) | Klónozza a jelenlegi objektumot |

### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben lévő műveletek számát. Csak olvasható int.

**Visszatér:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Visszaadja vagy beállítja a megadott indexű műveletet. Olvasás/írás [ColorOperation](../../com.aspose.slides/coloroperation).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Visszaadja vagy beállítja a megadott indexű műveletet. Olvasás/írás [ColorOperation](../../com.aspose.slides/coloroperation).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Új műveletet ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operation | int | Művelet típusa. |
| parameter | float | A művelet paramétere. |

**Visszatér:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Hozzáadott művelet.

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Új műveletet ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operation | int | Művelet típusa. |

**Visszatér:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Hozzáadott művelet.

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Beszúrja az új műveletet a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | int | Az index, ahová a művelet be lesz illesztve. |
| operation | int | Művelet típusa. |
| parameter | float | A művelet paramétere. |

**Visszatér:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Beszúrt művelet.

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Beszúrja az új műveletet a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | int | Az index, ahová a művelet be lesz illesztve. |
| operation | int | Művelet típusa. |

**Visszatér:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Beszúrt művelet.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a színműveletet a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő színművelet indexe. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes színműveletet.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Egy IGenericEnumerator, amely használható a gyűjtemény végigiterálásához.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Egy java.util.Iterator a teljes gyűjteményhez.

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

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (thread-safe). Csak olvasható boolean.

**Visszatér:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható Object.

**Visszatér:**
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Létrehoz egy másolatot a ColorOperationCollection gyűjteményről.

**Visszatér:**
java.lang.Object - Új [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) gyűjtemény.

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Klónozza a jelenlegi objektumot

**Visszatér:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Klón