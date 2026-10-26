---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt die Sammlung von Gruppen kombinierbarer Serien dar.
type: docs
url: /de/com.aspose.slides/ichartseriesgroupcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Stellt die Sammlung von Gruppen kombinierbarer Serien dar.

--------------------

1) Jede Gruppe von Serien enthält Serien mit kombinierbaren Typen. Gruppen von kombinierbaren Serientypen werden mit dem Aufzählungstyp CombinableSeriesTypesGroup definiert und beschrieben. Außerdem enthält jede Gruppe von Serien Serien, die entweder auf primären Achsen oder auf sekundären Achsen geplottet werden (nicht beide Fälle in einer Gruppe). Das Prinzip der Seriengruppierung basiert also auf einer Gruppierung nach den oben genannten Typgruppen und nach dem primären/sekundären Plottyp. 2) Eine Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind („Seriengruppeneigenschaften“). „Seriengruppeneigenschaften“ in der Klasse ChartSeriesGroup sind lesbar/schreibbar. Jede der „Seriengruppeneigenschaften“ kann in der Klasse ChartSeries eine schreibgeschützte Projektion haben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Ermittelt die Seriengruppe anhand einer Serie. |
| [get_Item(int index)](#get-Item-int-) | Ermittelt die Seriengruppe anhand des Index. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


Ermittelt die Seriengruppe anhand einer Serie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Rückgabewert:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


Ermittelt die Seriengruppe anhand des Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)