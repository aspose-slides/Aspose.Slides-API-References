---
title: ISequenceCollection
second_title: Aspose.Slides Androidhoz Java API Referencia
description: Interaktív szekvenciák gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/isequencecollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

A interaktív szekvenciák gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a gyűjtemény elemeinek számát Csak olvasható int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Új interaktív szekvenciát ad hozzá. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Eltávolítja a megadott szekvenciát a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a szekvenciát a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes szekvenciát a gyűjteményből. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy szekvenciát a megadott indexnél. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Visszaadja a gyűjtemény elemeinek számát Csak olvasható int.

**Visszatérési érték:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

Új interaktív szekvenciát ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) |

**Visszatérési érték:**
[ISequence](../../com.aspose.slides/isequence) - Új szekvencia [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

Eltávolítja a megadott szekvenciát a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Eltávolítandó szekvencia. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a szekvenciát a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe a gyűjteményben int |
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes szekvenciát a gyűjteményből.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

Visszaad egy szekvenciát a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Elem indexe. |

**Visszatérési érték:**
[ISequence](../../com.aspose.slides/isequence) - A [ISequence](../../com.aspose.slides/isequence) objektum.