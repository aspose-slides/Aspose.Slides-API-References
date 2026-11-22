---
title: IDataLabelCollection class
second_title: Aspose.Slides dla Pythona poprzez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection klasa

Reprezentuje etykiety serii.

Typ IDataLabelCollection udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Zwraca domyślny format wszystkich etykiet danych w zbiorze.<br/>            Tylko do odczytu [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Reprezentuje format linii prowadzących etykiet danych.<br/>             Tylko do odczytu [`IChartLinesFormat`](/slides/python-net/pl/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/is_visible/) | False oznacza, że etykieta danych nie jest widoczna domyślnie (a więc wszystkie flagi Show*-flags (ShowValue, ...) własności DefaultDataLabelFormat są false).<br/>            Tylko do odczytu **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Pobiera liczbę widocznych etykiet danych w zbiorze.<br/>            Tylko do odczytu **int**. |
| [`count`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/count/) | Pobiera liczbę wszystkich etykiet danych w zbiorze.<br/>            Tylko do odczytu **int**. |
| [`parent_series`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/parent_series/) | Zwraca nadrzędną serię wykresu.<br/>            Tylko do odczytu [`IChartSeries`](/slides/python-net/pl/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | Pobiera lub ustawia domyślny typ kształtu dla etykiet danych.<br/>             Zwraca [`ShapeType.NOT_DEFINED`](/slides/python-net/pl/aspose.slides/shapetype/NOT_DEFINED) jeśli nie zdefiniowano kształtu. |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Pobiera etykietę danych dla punktu danych o określonym indeksie.

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`hide(self)`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/hide/#) | Ukrywa etykietę danych domyślnie poprzez ustawienie wszystkich flag Show*-flags (ShowValue, ...) własności DefaultDataLabelFormat na stan false. IsVisible będzie false po tej operacji. |
| [`index_of(self, value)`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Zwraca indeks określonej DataLabel w zbiorze. |


### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)