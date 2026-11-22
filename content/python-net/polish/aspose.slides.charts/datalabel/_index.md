---
title: DataLabel class
second_title: Aspose.Slides dla Pythona przez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabel/
---
## DataLabel klasa

Represents a series labels.

The DataLabel type exposes the following members:

## Konstruktory

| Constructor | Description |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/pl/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Tworzy nową instancję klasy DataLabel. |

## Właściwości

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/datalabel/chart/) | Zwraca wykres nadrzędny.<br/>            Tylko do odczytu [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/pl/aspose.slides.charts/datalabel/is_visible/) | False oznacza, że etykieta danych nie jest widoczna (a więc wszystkie flagi Show*- (ShowValue, ...) są false).<br/>            Tylko do odczytu **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/pl/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Może zawierać bogato formatowany tekst. Jeśli ta właściwość nie jest None, to ta <br/>            wartość sformatowanego tekstu zastępuje automatycznie generowany tekst etykiety danych.<br/>            Automatycznie generowany tekst etykiety danych oznacza tekst zarządzany przez właściwości ShowSeriesName, <br/>            ShowValue, ... i formatowany przy użyciu właściwości TextFormatManager.TextFormat.<br/>            Tylko do odczytu [`ITextFrame`](/slides/python-net/pl/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/pl/aspose.slides.charts/datalabel/text_format/) | Zwraca format tekstu.<br/>            Tylko do odczytu [`IChartTextFormat`](/slides/python-net/pl/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/pl/aspose.slides.charts/datalabel/x/) | Zwraca lub ustawia współrzędną x tytułu jako ułamek szerokości wykresu.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides.charts/datalabel/y/) | Zwraca lub ustawia współrzędną y tytułu jako ułamek wysokości wykresu.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides.charts/datalabel/width/) | Zwraca lub ustawia szerokość tytułu jako ułamek szerokości wykresu.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides.charts/datalabel/height/) | Zwraca lub ustawia wysokość tytułu jako ułamek wysokości wykresu.<br/>            Odczyt/zapis **float**. |
| [`right`](/slides/python-net/pl/aspose.slides.charts/datalabel/right/) | Prawo.<br/>            Tylko do odczytu **float**. |
| [`bottom`](/slides/python-net/pl/aspose.slides.charts/datalabel/bottom/) | Dół.<br/>            Tylko do odczytu **float**. |
| [`data_label_format`](/slides/python-net/pl/aspose.slides.charts/datalabel/data_label_format/) | Zwraca format etykiety danych.<br/>            Tylko do odczytu [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/pl/aspose.slides.charts/datalabel/value_from_cell/) | Pobiera lub ustawia komórkę danych skoroszytu. Stosowane, jeśli właściwość IDataLabelFormat.ShowLabelValueFromCell ma wartość true. |
| [`label_shape_type`](/slides/python-net/pl/aspose.slides.charts/datalabel/label_shape_type/) | Pobiera lub ustawia typ kształtu etykiety danych.<br/>             Zwraca [`ShapeType.NOT_DEFINED`](/slides/python-net/pl/aspose.slides/shapetype/NOT_DEFINED) jeśli nie zdefiniowano kształtu. |
| [`actual_x`](/slides/python-net/pl/aspose.slides.charts/datalabel/actual_x/) | Określa rzeczywistą pozycję x (lewo) elementu wykresu względem lewego górnego narożnika wykresu.<br/>            Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. <br/>            Odczyt **float**. |
| [`actual_y`](/slides/python-net/pl/aspose.slides.charts/datalabel/actual_y/) | Określa rzeczywistą górę elementu wykresu względem lewego górnego narożnika wykresu.<br/>            Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. <br/>            Odczyt **float**. |
| [`actual_width`](/slides/python-net/pl/aspose.slides.charts/datalabel/actual_width/) | Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. <br/>            Odczyt **float**. |
| [`actual_height`](/slides/python-net/pl/aspose.slides.charts/datalabel/actual_height/) | Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. <br/>            Odczyt **float**. |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/datalabel/presentation/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/pl/aspose.slides.charts/datalabel/hide/#) | Ukrywa etykietę danych, ustawiając wszystkie flagi Show*- (ShowValue, ...) w stan false.<br/>            IsVisible będzie false po tym. |
| [`get_actual_label_text(self)`](/slides/python-net/pl/aspose.slides.charts/datalabel/get_actual_label_text/#) | Zwraca rzeczywisty tekst etykiety na podstawie ustawień DataLabelFormat lub wartości TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/pl/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inicjalizuje TextFrameForOverriding tekstem przekazanym w parametrze "text".<br/>            Jeśli TextFrameForOverriding jest już zainicjalizowany, po prostu zmienia jego tekst. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)