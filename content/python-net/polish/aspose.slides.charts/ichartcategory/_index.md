---
title: IChartCategory class
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartcategory/
---
## klasa IChartCategory

Reprezentuje kategorie wykresu.

Typ IChartCategory udostępnia następujące elementy:

## Właściwości

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/use_cell/) | Jeśli true, właściwość AsCell jest aktualna. Innymi słowy, arkusz jest używany do <br/>            przechowywania kategorii (ten przypadek obsługuje kategorię wielopoziomową).<br/>            Jeśli false, właściwość AsLiteral jest aktualna. Innymi słowy, arkusz NIE jest używany <br/>            do przechowywania kategorii (i ten przypadek nie obsługuje kategorii wielopoziomowych).<br/>            Tylko do odczytu **bool**. |
| [`as_cell`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/as_cell/) | Zwraca lub ustawia obiekt IChartDataCell.<br/>            Jeśli kategoria jest wielopoziomowa, używany jest obiekt IChartDataCell dla poziomu "0".<br/>            Odczyt/zapis [`IChartDataCell`](/slides/python-net/pl/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/as_literal/) | Zwraca lub ustawia AsLiteral, jeśli UseCell jest false.<br/>            Odczyt/zapis **any**. |
| [`value`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/value/) | Jeśli UseCell jest true, ta właściwość reprezentuje właściwość AsCell.Value.<br/>            Jeśli UseCell jest false, ta właściwość reprezentuje właściwość AsLiteral.<br/>            Odczyt/zapis **any**. |
| [`cached_value`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/cached_value/) | Pobiera zapisaną w pamięci wartość kategorii wykresu.<br/>            Tylko do odczytu [`ICachedChartValue`](/slides/python-net/pl/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/grouping_levels/) | Zarządzany kontener wartości poziomów grupowania kategorii wykresu.<br/>            Kategoria wielopoziomowa zawiera więcej niż jeden poziom grupowania.<br/>            Indeksowanie poziomów grupowania rozpoczyna się od zera.<br/>            Tylko do odczytu [`IChartCategoryLevelsManager`](/slides/python-net/pl/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metody

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/pl/aspose.slides.charts/ichartcategory/remove/#) | Usuwa kategorię z wykresu. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)