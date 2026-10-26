---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje kolekcję grup kombinowalnych serii.
type: docs
url: /pl/com.aspose.slides/ichartseriesgroupcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Reprezentuje kolekcję grup kombinowalnych serii.

--------------------

1) Każda grupa serii zawiera serie o kombinowalnych typach. Grupy kombinowalnych typów serii są definiowane i opisane przy pomocy wyliczenia CombinableSeriesTypesGroup enum. Ponadto każda grupa serii zawiera serie, które są rysowane albo na głównych osiach, albo na osiach dodatkowych (nie oba przypadki w jednej grupie). Zatem zasada grupowania serii polega na grupowaniu według wymienionych wyżej grup typów oraz według typu wykreślania głównego/dodatkowego. 2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie („series group properties”). „Series group properties” w klasie ChartSeriesGroup jest read/write. Każda z „series group properties” może mieć projekcję read-only w klasie ChartSeries.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Pobiera grupę serii na podstawie serii. |
| [get_Item(int index)](#get-Item-int-) | Pobiera grupę serii na podstawie indeksu. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


Pobiera grupę serii na podstawie serii.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Zwraca:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


Pobiera grupę serii na podstawie indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)