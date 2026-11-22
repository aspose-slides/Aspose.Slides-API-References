---
title: DataLabelCollection class
second_title: Aspose.Slides dla Pythona przez .NET - dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection klasa

Reprezentuje etykiety serii.

Typ DataLabelCollection udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/chart/) | Zwraca wykres nadrzędny.<br/>            Tylko do odczytu [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/is_visible/) | False oznacza, że etykieta danych nie jest widoczna domyślnie (i tak wszystkie <br/>            Show*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat są false).<br/>            Tylko do odczytu **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Pobiera liczbę widocznych etykiet danych w kolekcji.<br/>            Tylko do odczytu **int**. |
| [`count`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/count/) | Pobiera liczbę wszystkich etykiet danych w kolekcji.<br/>            Tylko do odczytu **int**. |
| [`default_data_label_format`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Pobiera domyślny format etykiety danych.<br/>            Tylko do odczytu [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Reprezentuje format linii prowadzących etykiet danych.<br/>             Tylko do odczytu [`IChartLinesFormat`](/slides/python-net/pl/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/parent_series/) | Pobiera serię nadrzędną.<br/>            Tylko do odczytu [`IChartSeries`](/slides/python-net/pl/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | Pobiera lub ustawia domyślny typ kształtu dla etykiet danych.<br/>             Zwraca [`ShapeType.NOT_DEFINED`](/slides/python-net/pl/aspose.slides/shapetype/NOT_DEFINED) jeśli nie określono kształtu. |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/presentation/) |  |

Pobiera etykietę danych dla punktu danych o określonym indeksie.

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`hide(self)`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/hide/#) | Ukryj etykietę danych domyślnie, ustawiając wszystkie flagi Show*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat w stan false.<br/>            IsVisible będzie false po tej operacji. |
| [`index_of(self, value)`](/slides/python-net/pl/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Zwraca indeks określonej DataLabel w kolekcji. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)