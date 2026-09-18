---
title: DataLabel class
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabel/
---
## DataLabel klasa

Reprezentuje etykiety serii.

Typ DataLabel udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/pl/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Tworzy nową instancję klasy DataLabel. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/datalabel/chart/) | Zwraca wykres nadrzędny.<br/>            Tylko do odczytu [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/pl/aspose.slides.charts/datalabel/is_visible/) | False oznacza, że etykieta danych nie jest widoczna (i wszystkie flagi Show*- (ShowValue, ...) są false).<br/>            Tylko do odczytu **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/pl/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Może zawierać bogato sformatowany tekst. Jeśli ta właściwość nie jest None, to ten <br/>            sformatowany tekst zastępuje automatycznie generowany tekst etykiety danych.<br/>            Automatycznie generowany tekst etykiety danych oznacza tekst zarządzany przez właściwości ShowSeriesName, <br/>            ShowValue, ... i formatowany przy użyciu właściwości TextFormatManager.TextFormat.<br/>            Tylko do odczytu [`ITextFrame`](/slides/python-net/pl/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/pl/aspose.slides.charts/datalabel/text_format/) | Zwraca format tekstu.<br/>            Tylko do odczytu [`IChartTextFormat`](/slides/python-net/pl/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/pl/aspose.slides.charts/datalabel/x/) | Zwraca lub ustawia współrzędną x tytułu jako ułamek szerokości wykresu.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides.charts/datalabel/y/) | Zwraca lub ustawia współrzędną y tytułu jako ułamek wysokości wykresu.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides.charts/datalabel/width/) | Zwraca lub ustawia szerokość tytułu jako ułamek szerokości wykresu.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides.charts/datalabel/height/) | Zwraca lub ustawia wysokość tytułu jako ułamek wysokości wykresu.<br/>            Odczyt/zapis **float**. |
| [`right`](/slides/python-net/pl/aspose.slides.charts/datalabel/right/) | Prawo.<br/>            Tylko do odczytu **float**. |
| [`bottom`](/slides/python-net/pl/aspose.slides.charts/datalabel/bottom/) | Dół.<br/>            Tylko do odczytu **float**. |
| [`data_label_format`](/slides/python-net/pl/aspose.slides.charts/datalabel/data_label_format/) | Zwraca format etykiety danych.<br/>            Tylko do odczytu [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/pl/aspose.slides.charts/datalabel/value_from_cell/) | Pobiera lub ustawia komórkę danych skoroszytu. Stosowane, jeśli właściwość IDataLabelFormat.ShowLabelValueFromCell ma wartość true. |
| [`actual_x`](/slides/python-net/pl/aspose.slides.charts/datalabel/actual_x/) | Określa rzeczywistą pozycję x (lewa) elementu wykresu względem lewego górnego narożnika wykresu.<br/>            Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. <br/>            Odczyt **float**. |
| [`actual_y`](/slides/python-net/pl/aspose.slides.charts/datalabel/actual_y/) | Określa rzeczywistą górną pozycję elementu wykresu względem lewego górnego narożnika wykresu.<br/>            Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. <br/>            Odczyt **float**. |
| [`actual_width`](/slides/python-net/pl/aspose.slides.charts/datalabel/actual_width/) | Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. <br/>            Odczyt **float**. |
| [`actual_height`](/slides/python-net/pl/aspose.slides.charts/datalabel/actual_height/) | Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed pobraniem rzeczywistych wartości. <br/>            Odczyt **float**. |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/datalabel/presentation/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`hide(self)`](/slides/python-net/pl/aspose.slides.charts/datalabel/hide/#) | Ukrywa etykietę danych, ustawiając wszystkie flagi Show*- (ShowValue, ...) na stan false.<br/>            IsVisible będzie false po tej operacji. |
| [`get_actual_label_text(self)`](/slides/python-net/pl/aspose.slides.charts/datalabel/get_actual_label_text/#) | Zwraca rzeczywisty tekst etykiety na podstawie ustawień DataLabelFormat lub wartości TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/pl/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inicjalizuje TextFrameForOverriding tekstem z parametru "text".<br/>            Jeśli TextFrameForOverriding jest już zainicjowany, po prostu zmienia jego tekst. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)