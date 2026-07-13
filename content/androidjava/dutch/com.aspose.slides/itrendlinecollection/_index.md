---
title: ITrendlineCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van TrendlineEx voor
type: docs
url: /nl/com.aspose.slides/itrendlinecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Stelt een verzameling van TrendlineEx voor
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [getCount()](#getCount--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [add(int trendlineType)](#add-int-) | Voegt de nieuwe Trendline toe aan het einde van een collectie en retourneert deze. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Verwijdert de opgegeven waarde. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


Haalt het element op op de opgegeven index. Alleen-lezen [ITrendline](../../com.aspose.slides/itrendline).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen int.

**Retourneert:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Voegt de nieuwe Trendline toe aan het einde van een collectie en retourneert deze.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| trendlineType | int | Trendline-type [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Retourneert:**
[ITrendline](../../com.aspose.slides/itrendline) - Nieuwe Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


Verwijdert de opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline om te verwijderen [ITrendline](../../com.aspose.slides/itrendline) |