---
title: TrendlineCollection
second_title: Aspose.Slides für Android über Java API-Referenz
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
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [add(int trendlineType)](#add-int-) | Fügt die neue Trendline am Ende einer Sammlung hinzu und gibt sie zurück. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Entfernt den angegebenen Wert. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [getCount()](#getCount--) | Gibt die tatsächlich in der Sammlung enthaltene Elementanzahl zurück. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Ruft das Element am angegebenen Index ab. Nur-Lesen [Trendline](../../com.aspose.slides/trendline).

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

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Ein java.util.Iterator für die gesamte Sammlung.
### getCount() {#getCount--}
```
public final int getCount()
```

Gibt die tatsächlich in der Sammlung enthaltene Elementanzahl zurück. Nur-Lesen int.

**Rückgabewert:**
int