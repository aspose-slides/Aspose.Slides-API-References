---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides für Android über Java API-Referenz
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

1) Jede Gruppe von Serien enthält Serien mit kombinierbaren Typen. Gruppen von kombinierbaren Seriotypen werden mit dem Enum **CombinableSeriesTypesGroup** definiert und beschrieben. Außerdem enthält jede Gruppe von Serien Serien, die entweder auf Primärachsen oder auf Sekundärachsen (nicht beide Fälle in einer Gruppe) geplottet werden. Das Prinzip der Seriengruppierung basiert also auf den oben genannten Typgruppen und dem Primär-/Sekundär-Plott-Typ.  
2) Eine Gruppe von Serien enthält einige Serien-Eigenschaften, die für jede Serie in der Gruppe gemeinsam sind („Seriengruppen-Eigenschaften“). „Seriengruppen-Eigenschaften“ in der **ChartSeriesGroup**-Klasse sind Lese-/Schreib-Zugriff. Jede der „Seriengruppen-Eigenschaften“ kann in der **ChartSeries**-Klasse eine schreibgeschützte Projektion besitzen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Ruft die Seriengruppe anhand einer Serie ab. |
| [get_Item(int index)](#get-Item-int-) | Ruft die Seriengruppe anhand des Index ab. |
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