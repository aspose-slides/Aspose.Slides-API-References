---
title: ControlCollection
second_title: Aspose.Slides Java API referenciája
description: ActiveX vezérlők gyűjteménye.
type: docs
url: /hu/com.aspose.slides/controlcollection/
---
**Öröklés:**
java.lang.Object

**Az összes implementált interfész:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

ActiveX vezérlők gyűjteménye.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | A gyűjteményben lévő objektumok számát adja vissza. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Új vezérlőt hoz létre és ad hozzá a gyűjteményhez. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Eltávolít egy ActiveX vezérlőt a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy megadott pozícióban tárolt ActiveX vezérlőt a gyűjteményből. |
| [clear()](#clear--) | Az összes vezérlőt eltávolítja a gyűjteményből. |
| [get_Item(int index)](#get-Item-int-) | A megadott pozícióban lévő vezérlőt adja vissza. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | A teljes gyűjteményt a megadott tömbbe másolja. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


A gyűjteményben lévő objektumok számát adja vissza. Csak olvasható int.

**Visszatér:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```


Új vezérlőt hoz létre és ad hozzá a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| controlType | int | A hozzáadandó vezérlő típusa. |
| x | float | A forma bal oldalának X-koordinátája. |
| y | float | A forma felső oldalának Y-koordinátája. |
| width | float | A forma keretének szélessége. |
| height | float | A forma keretének magassága. |

**Visszatér:**
[IControl](../../com.aspose.slides/icontrol) - Létrehozott vezérlő.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```


Eltávolít egy ActiveX vezérlőt a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Eltávolítandó vezérlő. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolít egy megadott pozícióban tárolt ActiveX vezérlőt a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó vezérlő indexe. |

### clear() {#clear--}
```
public final void clear()
```


Az összes vezérlőt eltávolítja a gyűjteményből.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```


A megadott pozícióban lévő vezérlőt adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A vezérlő indexe. |

**Visszatér:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```


Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Egy java.util.Iterator a teljes gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


A teljes gyűjteményt a megadott tömbbe másolja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb |
| index | int | Az index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatér:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaad egy Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject