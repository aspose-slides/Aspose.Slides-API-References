---
title: IChartCategory class
second_title: Aspose.Slides dla Pythona poprzez .NET API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartcategory/
---
## IChartCategory klasa

Reprezentuje kategorie wykresu.

Typ IChartCategory udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`use_cell`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/use_cell/) | If true then AsCell property is actual. In other words, worksheet is used for <br/>            przechowywania kategorii (ten przypadek obsługuje kategorię wielopoziomową).<br/>            If false then AsLiteral property is actual. In other words, worksheet is NOT used <br/>            do przechowywania kategorii (i ten przypadek nie obsługuje kategorii wielopoziomowych).<br/>            Tylko do odczytu **bool**. |
| [`as_cell`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/as_cell/) | Zwraca lub ustawia obiekt IChartDataCell.<br/>            Jeśli kategoria jest wielopoziomowa, wtedy używany jest obiekt IChartDataCell dla poziomu "0".<br/>            Odczyt/zapis [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/as_literal/) | Zwraca lub ustawia AsLiteral, jeśli UseCell jest false.<br/>            Odczyt/zapis **any**. |
| [`value`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/value/) | Jeśli UseCell jest true, wtedy ta właściwość reprezentuje właściwość AsCell.Value.<br/>            Jeśli UseCell jest false, wtedy ta właściwość reprezentuje właściwość AsLiteral.<br/>            Odczyt/zapis **any**. |
| [`grouping_levels`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/grouping_levels/) | Zarządzany kontener wartości poziomów grupowania kategorii wykresu.<br/>            Kategoria wielopoziomowa zawiera więcej niż jeden poziom grupowania.<br/>            Indeksowanie poziomów grupowania zaczyna się od zera.<br/>            Tylko do odczytu [`IChartCategoryLevelsManager`](/slides/python-net/pl/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`remove(self)`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/remove/#) | Usuwa kategorię z wykresu. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)