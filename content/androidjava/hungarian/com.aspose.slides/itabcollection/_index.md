---
title: ITabCollection
second_title: Aspose.Slides Androidra a Java API hivatkozás szerint
description: A tabok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/itabcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Egy Tabok gyűjteményét képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [add(double position, int align)](#add-double-int-) | Tab-ot ad a gyűjteményhez. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Tab-ot ad a gyűjteményhez. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjtemény megadott indexű elemét. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


A megadott indexű elemet adja vissza. Csak olvasható [ITab](../../com.aspose.slides/itab).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


Tab-ot ad a gyűjteményhez.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | double | Tab pozíció. |
| align | int | Tab igazítás. |

**Visszatérési érték:**
[ITab](../../com.aspose.slides/itab) - Hozzáadott Tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```


Tab-ot ad a gyűjteményhez.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | A gyűjtemény végén hozzáadandó Tab objektum. |

**Visszatérési érték:**
int - A tab hozzáadásának indexe.
### clear() {#clear--}
```
public abstract void clear()
```


Eltávolítja a gyűjtemény összes elemét.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja a gyűjtemény megadott indexű elemét.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | A eltávolítandó elem nulláralapú indexe. |