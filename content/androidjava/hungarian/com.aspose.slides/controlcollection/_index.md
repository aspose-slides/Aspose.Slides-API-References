---
title: ControlCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: ActiveX vezérlők gyűjteménye.
type: docs
url: /hu/com.aspose.slides/controlcollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

ActiveX vezérlőket tartalmazó gyűjtemény.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszatér a gyűjteményben lévő objektumok számával. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Létrehoz és hozzáad egy új vezérlőt a gyűjteményhez. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Eltávolít egy ActiveX vezérlőt a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy megadott pozícióban tárolt ActiveX vezérlőt a gyűjteményből. |
| [clear()](#clear--) | Eltávolít minden vezérlőt a gyűjteményből. |
| [get_Item(int index)](#get-Item-int-) | Visszatér egy vezérlővel a megadott pozícióban. |
| [iterator()](#iterator--) | Visszatér egy felsorolási objektummal, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszatér egy java iterátorral az egész gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja az egész gyűjteményt a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszatér a szinkronizáció gyökérével. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Visszatér a gyűjteményben lévő objektumok számával. Csak olvasható int.

**Visszatér:**  
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Létrehoz egy új vezérlőt és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| controlType | int | A hozzáadandó vezérlő típusa. |
| x | float | A forma keret bal oldalának X-koordinátája. |
| y | float | A forma keret felső oldalának Y-koordinátája. |
| width | float | A forma keret szélessége. |
| height | float | A forma keret magassága. |

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
| item | [IControl](../../com.aspose.slides/icontrol) | Az eltávolítandó vezérlő. |
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

Eltávolít minden vezérlőt a gyűjteményből.
### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Visszatér a megadott pozícióban lévő vezérlővel.

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

Visszatér egy felsorolási objektummal, amely végigiterál a gyűjteményen.

**Visszatér:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Az IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Visszatér egy java iterátorral az egész gyűjteményhez.

**Visszatér:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Egy java.util.Iterator az egész gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja az egész gyűjteményt a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb |
| index | int | Az index a cél tömbben. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatér:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszatér a szinkronizáció gyökérével. Csak olvasható Object.

**Visszatér:**  
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszatér a Parent_Immediate objektummal. Csak olvasható IDOMObject.

**Visszatér:**  
com.aspose.slides.IDOMObject