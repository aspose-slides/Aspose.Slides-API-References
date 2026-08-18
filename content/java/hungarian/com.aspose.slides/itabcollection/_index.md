---
title: ITabCollection
second_title: Aspose.Slides Java API-referencia
description: Fülek gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/itabcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

A fülek gyűjteményét reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekérdezi az elemet a megadott indexen. |
| [add(double position, int align)](#add-double-int-) | Hozzáad egy Tab-ot a gyűjteményhez. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Hozzáad egy Tab-ot a gyűjteményhez. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjteményben a megadott indexű elemet. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

Lekérdezi az elemet a megadott indexen. Csak olvasható [ITab](../../com.aspose.slides/itab).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

Hozzáad egy Tab-ot a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | double | A Tab pozíciója. |
| align | int | A Tab igazítása. |

**Visszatérési érték:**
[ITab](../../com.aspose.slides/itab) - Hozzáadott fül.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

Hozzáad egy Tab-ot a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | A gyűjtemény végére hozzáadandó Tab objektum. |

**Visszatérési érték:**
int - Az index, amelyen a fül hozzá lett adva.
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja a gyűjtemény összes elemét.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a gyűjteményben a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő elem nulla alapú indexe. |