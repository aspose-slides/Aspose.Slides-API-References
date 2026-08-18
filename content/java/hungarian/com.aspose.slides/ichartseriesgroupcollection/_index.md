---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides Java API referencia
description: A kombinálható sorozatok csoportjainak gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ichartseriesgroupcollection/
---
**Összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

A kombinálható sorozatok csoportjainak gyűjteményét képviseli.

--------------------

1) Minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek kombinálható típusúak. A kombinálható sorozattípusok csoportjait a CombinableSeriesTypesGroup enumeráció definiálja és írja le. Emellett minden sorozatcsoport olyan sorozatot tartalmaz, amely vagy elsődleges, vagy másodlagos tengelyen kerül ábrázolásra (nem mindkettő egy csoportban). Így a sorozatcsoportosítás elve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás.
2) A sorozatcsoport néhány sorozatjellemzőt tartalmaz, amelyek közösek a csoport minden sorozata számára („sorozatcsoport-jellemzők”). A „sorozatcsoport-jellemzők” a ChartSeriesGroup osztályban olvasás/írás. Minden „sorozatcsoport-jellemző” rendelkezhet egy csak olvasható vetülettel a ChartSeries osztályban.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Lekéri a sorozatcsoportot a sorozat alapján. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a sorozatcsoportot index alapján. |

### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

Lekéri a sorozatcsoportot a sorozat alapján.

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

Lekéri a sorozatcsoportot index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)