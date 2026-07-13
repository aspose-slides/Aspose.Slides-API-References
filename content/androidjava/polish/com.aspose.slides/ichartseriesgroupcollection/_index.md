---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides dla Androida poprzez Odniesienie API Java
description: Reprezentuje kolekcję grup łączonych serii.
type: docs
url: /pl/com.aspose.slides/ichartseriesgroupcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Reprezentuje kolekcję grup łączonych serii.

--------------------

1) Każda grupa serii zawiera serie z łączonymi typami. Grupy typów łączonych serii są definiowane i opisywane przy użyciu wyliczenia CombinableSeriesTypesGroup. Ponadto każda grupa serii zawiera serie, które są wykreślane na osi pierwszorzędnej lub na osi drugorzędnej (nie oba przypadki w jednej grupie). Zatem zasada grupowania serii polega na grupowaniu według wyżej wymienionych grup typów oraz według typu wykreślenia pierwszorzędny/ drugorzędny. 2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”). „Właściwości grupy serii” w klasie ChartSeriesGroup są odczytywalne i zapisywalne. Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Pobiera grupę serii według serii. |
| [get_Item(int index)](#get-Item-int-) | Pobiera grupę serii według indeksu. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

Pobiera grupę serii według serii.

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

Pobiera grupę serii według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)