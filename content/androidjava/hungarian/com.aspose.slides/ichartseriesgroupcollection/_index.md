---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides for Android – Java API Referencia
description: A kombinálható sorozatok csoportjainak gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ichartseriesgroupcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

A kombinálható sorozatok csoportjainak gyűjteményét képviseli.

--------------------

1) Minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek kombinálható típusúak. A kombinálható sorozattípusok csoportjait a CombinableSeriesTypesGroup enum határozza meg és írja le. Emellett minden sorozatcsoport olyan sorozatot tartalmaz, amely vagy az elsődleges tengelyen, vagy a másodlagos tengelyen kerül ábrázolásra (nem mindkettő egy csoportban). Tehát a sorozatcsoportosítás elve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolás típusa szerinti csoportosítás.
2) A sorozatcsoport bizonyos sorozattulajdonságokat tartalmaz, amelyek minden sorozatra jellemzőek a csoporton belül (“sorozatcsoport tulajdonságok”). A “sorozatcsoport tulajdonságok” a ChartSeriesGroup osztályban olvasható/írható. Minden “sorozatcsoport tulajdonságnak” lehet csak-olvasású vetülete a ChartSeries osztályban.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | A sorozatcsoportot a sorozat alapján adja vissza. |
| [get_Item(int index)](#get-Item-int-) | A sorozatcsoportot index alapján adja vissza. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


A sorozatcsoportot a sorozat alapján adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Visszatérési érték:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


A sorozatcsoportot index alapján adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)