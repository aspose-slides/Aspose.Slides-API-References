---
title: ChartCategoryCollection class
second_title: Aspose.Slides dla Pythona poprzez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection klasa

Reprezentuje kolekcję [`ChartCategory`](/slides/python-net/pl/aspose.slides.charts/chartcategory)

Typ ChartCategoryCollection udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`use_cells`](/slides/python-net/pl/aspose.slides.charts/chartcategorycollection/use_cells/) | Jeśli true, to worksheet jest używany do przechowywania kategorii (ten przypadek obsługuje wielopoziomowe kategorie).<br/>            Jeśli false, to worksheet NIE jest używany do przechowywania wartości (i ten przypadek nie obsługuje <br/>            wielopoziomowych kategorii).<br/>            Odczyt/zapis **bool**. |
| [`grouping_level_count`](/slides/python-net/pl/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Zwraca liczbę używanych poziomów grupowania kategorii.<br/>            Jest większa niż jeden dla wielopoziomowych kategorii.<br/>            Tylko do odczytu **int**. |

Pobiera element o określonym indeksie.

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/pl/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Jeśli kategoria istnieje w kolekcji, zwraca ją. W przeciwnym razie tworzy nową kategorię wykresu z <br/>            [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell) i dodaje ją do kolekcji. |
| [`add(self, value)`](/slides/python-net/pl/aspose.slides.charts/chartcategorycollection/add/#any) | Tworzy nowy [`ChartCategory`](/slides/python-net/pl/aspose.slides.charts/chartcategory) z wartości i dodaje go do kolekcji. |
| [`index_of(self, value)`](/slides/python-net/pl/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Wyszukuje określony [`ChartCategory`](/slides/python-net/pl/aspose.slides.charts/chartcategory) i zwraca indeks zerowy pierwszego wystąpienia w całej kolekcji. |
| [`remove(self, value)`](/slides/python-net/pl/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Usuwa określoną wartość. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Usuwa element o podanym indeksie. |
| [`clear(self)`](/slides/python-net/pl/aspose.slides.charts/chartcategorycollection/clear/#) | Usuwa wszystkie elementy z kolekcji. |

### Zobacz także
* klasa [`ChartCategory`](/slides/python-net/pl/aspose.slides.charts/chartcategory)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)