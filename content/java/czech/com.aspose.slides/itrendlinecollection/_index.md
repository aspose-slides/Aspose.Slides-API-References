---
title: ITrendlineCollection
second_title: Aspose.Slides pro Java API Reference
description: Representuje kolekci TrendlineEx
type: docs
url: /cs/com.aspose.slides/itrendlinecollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Reprezentuje kolekci TrendlineEx
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na určeném indexu. |
| [getCount()](#getCount--) | Získá počet prvků skutečně obsažených v kolekci. |
| [add(int trendlineType)](#add-int-) | Přidá novou Trendline na konec kolekce a vrátí ji. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Odstraní zadanou hodnotu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


Získá prvek na určeném indexu. Pouze ke čtení [ITrendline](../../com.aspose.slides/itrendline).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Získá počet prvků skutečně obsažených v kolekci. Pouze ke čtení int.

**Návratová hodnota:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Přidá novou Trendline na konec kolekce a vrátí ji.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| trendlineType | int | Typ Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Návratová hodnota:**
[ITrendline](../../com.aspose.slides/itrendline) - Nová Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


Odstraní zadanou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline k odstranění [ITrendline](../../com.aspose.slides/itrendline) |