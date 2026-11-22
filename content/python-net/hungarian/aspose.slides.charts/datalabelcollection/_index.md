---
title: DataLabelCollection class
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection osztály

Egy sor címkéit reprezentálja.

A DataLabelCollection típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/chart/) | Visszaadja a szülő diagramot.<br/>            Csak olvasható [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/is_visible/) | A hamis érték azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és így a DefaultDataLabelFormat tulajdonság összes Show*-jelzője (ShowValue, ...) hamis).<br/>            Csak olvasható **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Lekéri a gyűjteményben lévő látható adatcímkék számát.<br/>            Csak olvasható **int**. |
| [`count`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/count/) | Lekéri a gyűjteményben lévő összes adatcímke számát.<br/>            Csak olvasható **int**. |
| [`default_data_label_format`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Lekéri az alapértelmezett adatcímke formátumot.<br/>            Csak olvasható [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/leader_lines_format/) | A adatcímke vezetővonalak formátumát reprezentálja.<br/>             Csak olvasható [`IChartLinesFormat`](/slides/python-net/hu/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/parent_series/) | Lekéri a szülő sorozatot.<br/>            Csak olvasható [`IChartSeries`](/slides/python-net/hu/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | Lekéri vagy beállítja az adatcímkék alapértelmezett alakzat típusát.<br/>             Visszaadja [`ShapeType.NOT_DEFINED`](/slides/python-net/hu/aspose.slides/shapetype/NOT_DEFINED) értéket, ha nincs meghatározott alakzat. |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/presentation/) |  |

Lekéri a megadott indexű adatpont adatcímkéjét.

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`hide(self)`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/hide/#) | Az adatcímkét alapértelmezés szerint rejtve teszi minden Show*-jelző (ShowValue, ...) a DefaultDataLabelFormat tulajdonságnál false állapotba állításával.<br/>            Az IsVisible ezután hamis lesz. |
| [`index_of(self, value)`](/slides/python-net/hu/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Visszaadja a megadott DataLabel indexét a gyűjteményben. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)