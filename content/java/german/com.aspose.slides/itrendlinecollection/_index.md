---
title: ITrendlineCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von TrendlineEx dar
type: docs
url: /de/com.aspose.slides/itrendlinecollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Stellt eine Sammlung von TrendlineEx dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [getCount()](#getCount--) | Gibt die tatsächliche Anzahl der in der Sammlung enthaltenen Elemente zurück. |
| [add(int trendlineType)](#add-int-) | Fügt die neue Trendline am Ende einer Sammlung hinzu und gibt sie zurück. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Entfernt den angegebenen Wert. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

Gibt das Element am angegebenen Index zurück. Nur lesbar [ITrendline](../../com.aspose.slides/itrendline).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Gibt die tatsächliche Anzahl der in der Sammlung enthaltenen Elemente zurück. Nur lesbarer int.

**Rückgabewert:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

Fügt die neue Trendline am Ende einer Sammlung hinzu und gibt sie zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| trendlineType | int | Trendline-Typ [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Rückgabewert:**
[ITrendline](../../com.aspose.slides/itrendline) - Neue Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

Entfernt den angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline zu entfernen [ITrendline](../../com.aspose.slides/itrendline) |