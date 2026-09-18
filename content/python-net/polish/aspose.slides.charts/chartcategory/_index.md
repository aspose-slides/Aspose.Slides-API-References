---
title: ChartCategory class
second_title: Aspose.Slides dla Pythona via .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartcategory/
---
## ChartCategory klasa

Reprezentuje kategorie wykresu.

Typ ChartCategory udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`use_cell`](/slides/python-net/pl/aspose.slides.charts/chartcategory/use_cell/) | Jeśli true, właściwość AsCell jest aktualna. Inaczej, worksheet jest używany do <br/> przechowywania kategorii (ten przypadek obsługuje kategorię wielopoziomową).<br/> Jeśli false, właściwość AsLiteral jest aktualna. Inaczej, worksheet nie jest używany <br/> do przechowywania kategorii (i ten przypadek nie obsługuje kategorii wielopoziomowych).<br/> Tylko do odczytu **bool**. |
| [`as_cell`](/slides/python-net/pl/aspose.slides.charts/chartcategory/as_cell/) | Zwraca lub ustawia obiekt IChartDataCell.<br/>            Jeśli kategoria jest wielopoziomowa, używany jest obiekt IChartDataCell dla poziomu "0".<br/>            Odczyt/zapis [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/pl/aspose.slides.charts/chartcategory/as_literal/) | Zwraca lub ustawia obiekt AsLiteral.<br/>            Odczyt/zapis **any**. |
| [`value`](/slides/python-net/pl/aspose.slides.charts/chartcategory/value/) | Jeśli UseCell jest true, to ta właściwość reprezentuje właściwość AsCell.Value.<br/>            Jeśli UseCell jest false, to ta właściwość reprezentuje właściwość AsLiteral.<br/>            Odczyt/zapis **any**. |
| [`grouping_levels`](/slides/python-net/pl/aspose.slides.charts/chartcategory/grouping_levels/) | Zarządzany kontener wartości poziomów grupowania kategorii wykresu.<br/>            Kategoria wielopoziomowa zawiera więcej niż jeden poziom grupowania.<br/>            Indeksowanie poziomów grupowania zaczyna się od zera.<br/>            Tylko do odczytu [`IChartCategoryLevelsManager`](/slides/python-net/pl/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`remove(self)`](/slides/python-net/pl/aspose.slides.charts/chartcategory/remove/#) | Usuwa kategorię z wykresu. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)