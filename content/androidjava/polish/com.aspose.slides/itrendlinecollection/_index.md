---
title: ITrendlineCollection
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje kolekcję TrendlineEx
type: docs
url: /pl/com.aspose.slides/itrendlinecollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Represents a collection of TrendlineEx
## Metody

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o określonym indeksie. |
| [getCount()](#getCount--) | Pobiera liczbę elementów rzeczywiście zawartych w kolekcji. |
| [add(int trendlineType)](#add-int-) | Dodaje nową Trendline na końcu kolekcji i zwraca ją. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Usuwa określoną wartość. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


Pobiera element o określonym indeksie. Tylko do odczytu [ITrendline](../../com.aspose.slides/itrendline).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Pobiera liczbę elementów rzeczywiście zawartych w kolekcji. Tylko do odczytu int.

**Returns:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Dodaje nową Trendline na końcu kolekcji i zwraca ją.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trendlineType | int | Typ Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Returns:**
[ITrendline](../../com.aspose.slides/itrendline) - Nowa Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


Usuwa określoną wartość.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline do usunięcia [ITrendline](../../com.aspose.slides/itrendline) |