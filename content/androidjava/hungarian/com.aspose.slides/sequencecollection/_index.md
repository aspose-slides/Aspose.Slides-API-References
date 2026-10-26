---
title: SequenceCollection
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Az interaktív sorozatok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/sequencecollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Az interaktív sorozatok gyűjteményét reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a gyűjtemény elemeinek számát Csak olvasható int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Új interaktív sorozat hozzáadása. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Eltávolítja a megadott sorozatot a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a sorozatot a megadott indexen. |
| [clear()](#clear--) | Eltávolítja az összes sorozatot a gyűjteményből. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy sorozatot a megadott indexen. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort az egész gyűjteményhez. |
### getCount() {#getCount--}
```
public final int getCount()
```


Visszaadja a gyűjtemény elemeinek számát Csak olvasható int.

**Visszatérési érték:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


Új interaktív sorozat hozzáadása. Olvasás/írás [Sequence](../../com.aspose.slides/sequence).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Visszatérési érték:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


Eltávolítja a megadott sorozatot a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Eltávolítandó sorozat. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolítja a sorozatot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó sorozat indexe. |

### clear() {#clear--}
```
public final void clear()
```


Eltávolítja az összes sorozatot a gyűjteményből.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


Visszaad egy sorozatot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatérési érték:**
[ISequence](../../com.aspose.slides/isequence) - A [ISequence](../../com.aspose.slides/isequence) objektum.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Egy IGenericEnumerator, amelyet a gyűjtemény bejárásához használhat.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


Visszaad egy Java iterátort az egész gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Egy java.util.Iterator az egész gyűjteményhez.