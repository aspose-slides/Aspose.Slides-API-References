---
title: TrendlineCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje kolekci Trendline
type: docs
url: /cs/com.aspose.slides/trendlinecollection/
---
**Dědičnost:**  
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**  
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)  
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Představuje kolekci Trendline
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na určeném indexu. |
| [add(int trendlineType)](#add-int-) | Přidá novou Trendline na konec kolekce a vrátí ji. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Odstraní zadanou hodnotu. |
| [iterator()](#iterator--) | Vrátí enumerátor, který iteruje přes kolekci. |
| [iteratorJava()](#iteratorJava--) | Vrátí java iterátor pro celou kolekci. |
| [getCount()](#getCount--) | Získá počet prvků skutečně obsažených v kolekci. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Získá prvek na určeném indexu. Pouze pro čtení [Trendline](../../com.aspose.slides/trendline).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

Přidá novou Trendline na konec kolekce a vrátí ji.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| trendlineType | int |  |

**Vrací:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

Odstraní zadanou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

Vrátí enumerátor, který iteruje přes kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

Vrátí java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - java.util.Iterator pro celou kolekci.
### getCount() {#getCount--}
```
public final int getCount()
```

Získá počet prvků skutečně obsažených v kolekci. Pouze pro čtení int.

**Vrací:**
int