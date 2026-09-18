---
title: IDataLabel class
second_title: Aspose.Slides dla Pythona przez .NET API
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabel/
---
## IDataLabel klasa

Reprezentuje etykiety serii.

Typ IDataLabel udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_visible`](/slides/python-net/pl/aspose.slides.charts/idatalabel/is_visible/) | False oznacza, że etykieta danych nie jest widoczna (a więc wszystkie flagi Show*-flags (ShowValue, ...) są false).<br/>            Read-only **bool**. |
| [`data_label_format`](/slides/python-net/pl/aspose.slides.charts/idatalabel/data_label_format/) | Zwraca format etykiety danych.<br/>            Read-only [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/pl/aspose.slides.charts/idatalabel/value_from_cell/) | Pobiera lub ustawia komórkę danych skoroszytu. Stosowane, jeśli właściwość IDataLabelFormat.ShowLabelValueFromCell ma wartość true. |
| [`x`](/slides/python-net/pl/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/pl/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/pl/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/pl/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/pl/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/pl/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/pl/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/pl/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/pl/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/pl/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/pl/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/pl/aspose.slides.charts/idatalabel/actual_height/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`hide(self)`](/slides/python-net/pl/aspose.slides.charts/idatalabel/hide/#) | Ukrywa etykietę danych, ustawiając wszystkie flagi Show*-flags (ShowValue, ...) w stan false.<br/>            IsVisible będzie false po wykonaniu tej operacji. |
| [`get_actual_label_text(self)`](/slides/python-net/pl/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Zwraca aktualny tekst etykiety na podstawie ustawień DataLabelFormat lub wartości TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/pl/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)