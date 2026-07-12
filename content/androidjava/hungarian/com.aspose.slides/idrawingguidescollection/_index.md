---
title: IDrawingGuidesCollection
second_title: Aspose.Slides for Android Java API referencia
description: A beállítható rajzolósegédletek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/idrawingguidescollection/
---
**Minden implementált interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

A beállítható rajzolósegédletek gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a rajzolósegédletet index alapján. |
| [add(byte orientation, float position)](#add-byte-float-) | Hozzáadja a rajzolósegédletet a gyűjtemény végéhez. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a rajzolósegédletet a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
| [getCount()](#getCount--) | Lekéri az összes elem számát a gyűjteményben. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Visszaadja a rajzolósegédletet index alapján. Csak olvasható [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Hozzáadja a rajzolósegédletet a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| orientation | byte | A rajzolósegédlet tájolása. |
| position | float | A rajzolósegédlet pozíciója pontokban. |

**Visszatér:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja a rajzolósegédletet a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő rajzolósegédlet indexe. |

### clear() {#clear--}
```
public abstract void clear()
```


Eltávolítja az összes elemet a gyűjteményből.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Lekéri az összes elem számát a gyűjteményben. Csak olvasható int.

**Visszatér:**
int