---
title: ISequenceCollection
second_title: Aspose.Slides Java API referenciája
description: Az interaktív sorozatok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/isequencecollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Az interaktív sorozatok gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a gyűjtemény elemeinek számát. Csak olvasható int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Új interaktív sorozat hozzáadása. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Eltávolítja a megadott sorozatot a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a sorozatot a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes sorozatot a gyűjteményből. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy sorozatot a megadott indexnél. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Visszaadja a gyűjtemény elemeinek számát. Csak olvasható int.

**Returns:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


Új interaktív sorozat hozzáadása.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Alakzat objektum [IShape](../../com.aspose.slides/ishape) |

**Returns:**
[ISequence](../../com.aspose.slides/isequence) - Új sorozat [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


Eltávolítja a megadott sorozatot a gyűjteményből.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Eltávolítandó sorozat. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja a sorozatot a megadott indexnél.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe a gyűjteményben int |
### clear() {#clear--}
```
public abstract void clear()
```


Eltávolítja az összes sorozatot a gyűjteményből.
### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


Visszaad egy sorozatot a megadott indexnél.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Index of element. |

**Returns:**
[ISequence](../../com.aspose.slides/isequence) - A [ISequence](../../com.aspose.slides/isequence) objektum.