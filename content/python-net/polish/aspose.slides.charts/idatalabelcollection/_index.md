---
title: IDataLabelCollection class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – odniesienie API
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
| [`default_data_label_format`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Zwraca domyślny format wszystkich etykiet danych w kolekcji.<br/>            Tylko do odczytu [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Reprezentuje format linii łączących etykiety danych.<br/>             Tylko do odczytu [`IChartLinesFormat`](/slides/python-net/pl/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/is_visible/) | False oznacza, że etykieta danych nie jest widoczna domyślnie (a więc wszystkie <br/>            flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat są false).<br/>            Tylko do odczytu **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Zwraca liczbę widocznych etykiet danych w kolekcji.<br/>            Tylko do odczytu **int**. |
| [`count`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/count/) | Zwraca liczbę wszystkich etykiet danych w kolekcji.<br/>            Tylko do odczytu **int**. |
| [`parent_series`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/parent_series/) | Zwraca serię wykresu nadrzędnego.<br/>            Tylko do odczytu [`IChartSeries`](/slides/python-net/pl/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Zwraca etykietę danych dla punktu danych o określonym indeksie.

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`hide(self)`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/hide/#) | Ukryj etykietę danych domyślnie, ustawiając wszystkie flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat na stan false.<br/>            IsVisible będzie false po tym. |
| [`index_of(self, value)`](/slides/python-net/pl/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Zwraca indeks określonej DataLabel w kolekcji. |

### Zobacz również
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)