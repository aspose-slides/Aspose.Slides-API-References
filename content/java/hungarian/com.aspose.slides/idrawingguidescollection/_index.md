---
title: IDrawingGuidesCollection
second_title: Aspose.Slides Java API-referencia
description: A beállítható rajzvezetőket tartalmazó gyűjteményt képviseli.
type: docs
url: /hu/com.aspose.slides/idrawingguidescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

A beállítható rajzvezetőket tartalmazó gyűjteményt képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a rajzvezetőt az index alapján. |
| [add(byte orientation, float position)](#add-byte-float-) | Hozzáadja a rajzvezetőt a gyűjtemény végéhez. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a rajzvezetőt a megadott indexen. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben lévő összes elem számát. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

Visszaadja a rajzvezetőt az index alapján. Csak olvasható [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

Hozzáadja a rajzvezetőt a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| orientation | byte | A rajzvezető orientációja. |
| position | float | A rajzvezető helyzete pontokban. |

**Visszatérési érték:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a rajzvezetőt a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő rajzvezető indexe. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes elemet a gyűjteményből.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Lekéri a gyűjteményben lévő összes elem számát. Csak olvasható int.

**Visszatérési érték:**
int