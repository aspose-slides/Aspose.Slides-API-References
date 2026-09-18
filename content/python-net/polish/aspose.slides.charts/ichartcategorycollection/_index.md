---
title: IChartCategoryCollection class
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection klasa

Reprezentuje kolekcję [`IChartCategory`](/slides/python-net/pl/aspose.slides.charts/ichartcategory)

Typ IChartCategoryCollection udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`use_cells`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection/use_cells/) | Jeśli prawda, to worksheet jest używany do przechowywania kategorii (ten przypadek obsługuje multi-level categories).<br/>            Jeśli false, to worksheet NIE jest używany do przechowywania values (i ten przypadek nie obsługuje <br/>            multi-level categories).<br/>            Odczyt/zapis **bool**. |
| [`grouping_level_count`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Returns count of category grouping levels used.<br/>            Is more then one for multilevel categories.<br/>            Read-only **int**. |

Pobiera element pod określonym indeksem.

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Jeśli kategoria istnieje w kolekcji, zwróć ją. W przeciwnym razie tworzy nową chart category z <br/>            [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell) i dodaje ją do kolekcji. |
| [`add(self, value)`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection/add/#any) | Tworzy nowy [`IChartCategory`](/slides/python-net/pl/aspose.slides.charts/ichartcategory) z value i dodaje go do kolekcji. |
| [`index_of(self, value)`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Searches for the specified [`IChartCategory`](/slides/python-net/pl/aspose.slides.charts/ichartcategory) and returns the zero-based index of the first occurrence within the entire Collection |
| [`remove(self, value)`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Usuwa określoną wartość. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Usuwa element pod danym indeksem. |
| [`clear(self)`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection/clear/#) | Usuwa wszystkie elementy z kolekcji. |

### Zobacz także
* klasa [`IChartCategory`](/slides/python-net/pl/aspose.slides.charts/ichartcategory)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)