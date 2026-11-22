---
title: IDataLabelCollection class
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection osztály

Egy sor címkéit képviseli.

Az IDataLabelCollection típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Visszaadja az összes adatcímke alapértelmezett formátumát a gyűjteményben.<br/>            Csak olvasható [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Az adatcímkék vezető vonalai formátumát jelöli.<br/>             Csak olvasható [`IChartLinesFormat`](/slides/python-net/hu/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/is_visible/) | A hamis azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és ezért a DefaultDataLabelFormat tulajdonság összes Show*-jelzője (ShowValue, ...) hamis).<br/>            Csak olvasható **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Megkapja a látható adatcímkék számát a gyűjteményben.<br/>            Csak olvasható **int**. |
| [`count`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/count/) | Megkapja az összes adatcímke számát a gyűjteményben.<br/>            Csak olvasható **int**. |
| [`parent_series`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/parent_series/) | Visszaadja a szülő diagram sorozatot.<br/>            Csak olvasható [`IChartSeries`](/slides/python-net/hu/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | Megkapja vagy beállítja az adatcímkék alapértelmezett alakzat típusát.<br/>             Visszaadja [`ShapeType.NOT_DEFINED`](/slides/python-net/hu/aspose.slides/shapetype/NOT_DEFINED) ha nincs meghatározott alakzat. |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Megkapja a megadott indexű adatpont adatcímkéjét.

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`hide(self)`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/hide/#) | Az adatcímkét alapértelmezés szerint rejtetté teszi, a DefaultDataLabelFormat tulajdonság összes Show*-jelzőjét (ShowValue, ...) hamis állapotra állítva.<br/>            Az IsVisible ezután hamis lesz. |
| [`index_of(self, value)`](/slides/python-net/hu/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Visszaadja a megadott DataLabel indexét a gyűjteményben. |


### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)