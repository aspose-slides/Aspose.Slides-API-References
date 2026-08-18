---
title: ITrendlineCollection
second_title: Aspose.Slides Java API hivatkozás
description: TrendlineEx gyűjteményt képviseli
type: docs
url: /hu/com.aspose.slides/itrendlinecollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

TrendlineEx gyűjteményt képviseli
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexen. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben ténylegesen tárolt elemek számát. |
| [add(int trendlineType)](#add-int-) | Új Trendline-t ad a gyűjtemény végéhez és visszaadja. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Eltávolítja a megadott értéket. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

Lekéri az elemet a megadott indexen. Csak olvasható [ITrendline](../../com.aspose.slides/itrendline).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lekéri a gyűjteményben ténylegesen tárolt elemek számát. Csak olvasható int.

**Visszatér:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

Új Trendline-t ad a gyűjtemény végéhez és visszaadja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| trendlineType | int | Trendline típusa [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Visszatér:**
[ITrendline](../../com.aspose.slides/itrendline) - Új Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

Eltávolítja a megadott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Eltávolítandó Trendline [ITrendline](../../com.aspose.slides/itrendline) |