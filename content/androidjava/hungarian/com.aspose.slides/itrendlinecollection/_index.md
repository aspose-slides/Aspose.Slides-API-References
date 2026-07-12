---
title: ITrendlineCollection
second_title: Aspose.Slides for Android Java API hivatkozás
description: TrendlineEx gyűjteményt képvisel
type: docs
url: /hu/com.aspose.slides/itrendlinecollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

TrendlineEx gyűjteményt képvisel
## Módszerek

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexen. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben ténylegesen lévő elemek számát. |
| [add(int trendlineType)](#add-int-) | Hozzáad egy új Trendline-t a gyűjtemény végéhez, és visszaadja. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Eltávolítja a megadott értéket. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

Lekéri az elemet a megadott indexen. Csak olvasható [ITrendline](../../com.aspose.slides/itrendline).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lekéri a gyűjteményben ténylegesen lévő elemek számát. Csak olvasható int.

**Visszatérési érték:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

Hozzáad egy új Trendline-t a gyűjtemény végéhez, és visszaadja.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| trendlineType | int | Trendline típus [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Visszatérési érték:**
[ITrendline](../../com.aspose.slides/itrendline) - Új Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

Eltávolítja a megadott értéket.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline eltávolítandó [ITrendline](../../com.aspose.slides/itrendline) |