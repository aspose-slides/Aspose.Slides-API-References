---
title: TrendlineCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Trendline dar
type: docs
url: /de/com.aspose.slides/trendlinecollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Stellt eine Sammlung von Trendline dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Liefert das Element am angegebenen Index. |
| [add(int trendlineType)](#add-int-) | Fügt die neue Trendline am Ende einer Sammlung hinzu und gibt sie zurück. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Entfernt den angegebenen Wert. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen java iterator für die gesamte Sammlung zurück. |
| [getCount()](#getCount--) | Ermittelt die tatsächlich in der Sammlung enthaltene Elementanzahl. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```


Liefert das Element am angegebenen Index. Nur lesbar [Trendline](../../com.aspose.slides/trendline).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```


Fügt die neue Trendline am Ende einer Sammlung hinzu und gibt sie zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| trendlineType | int |  |

**Rückgabewert:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```


Entfernt den angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```


Gibt einen java iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Ein java.util.Iterator für die gesamte Sammlung.
### getCount() {#getCount--}
```
public final int getCount()
```


Ermittelt die tatsächlich in der Sammlung enthaltene Elementanzahl. Nur lesbar int.

**Rückgabewert:**
int