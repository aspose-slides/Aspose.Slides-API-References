---
title: Trendline class
second_title: Aspose.Slides dla Pythona przez .NET - odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/trendline/
---
## Trendline klasa

Klasa reprezentuje linię trendu serii wykresu

Typ Trendline udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`trendline_name`](/slides/python-net/pl/aspose.slides.charts/trendline/trendline_name/) | Uzyskuje lub ustawia nazwę linii trendu.<br/>            Odczyt/zapis **str**. |
| [`trendline_type`](/slides/python-net/pl/aspose.slides.charts/trendline/trendline_type/) | Uzyskuje lub ustawia typ linii trendu.<br/>            Odczyt/zapis [`TrendlineType`](/slides/python-net/pl/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/pl/aspose.slides.charts/trendline/format/) | Reprezentuje format linii trendu.<br/>            Odczyt/zapis [`IFormat`](/slides/python-net/pl/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/pl/aspose.slides.charts/trendline/backward/) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu rozciąga się przed<br/>            danymi serii, które są trendowane. Na wykresach punktowych i niepunktowych wartość może być dowolną nieujemną<br/>            wartością.<br/>            Odczyt/zapis **float**. |
| [`forward`](/slides/python-net/pl/aspose.slides.charts/trendline/forward/) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu rozciąga się po<br/>            danych serii, które są trendowane. Na wykresach punktowych i niepunktowych wartość może być dowolną nieujemną<br/>            wartością.<br/>            Odczyt/zapis **float**. |
| [`intercept`](/slides/python-net/pl/aspose.slides.charts/trendline/intercept/) | Określa wartość, w której linia trendu przecina oś y. Ta właściwość jest obsługiwana tylko wtedy,<br/>            gdy typ linii trendu to exp, linear lub poly.<br/>            Odczyt/zapis **float**. |
| [`display_equation`](/slides/python-net/pl/aspose.slides.charts/trendline/display_equation/) | Określa, że równanie linii trendu jest wyświetlane na wykresie (w tej samej etykiecie co wartość Rsquaredvalue).<br/>            Odczyt/zapis **bool**. |
| [`order`](/slides/python-net/pl/aspose.slides.charts/trendline/order/) | Określa kolejność wielomianowej linii trendu. Jest ignorowane dla innych typów linii trendu. Wartość musi być pomiędzy 2 a 6.<br/>            Odczyt/zapis **int**. |
| [`period`](/slides/python-net/pl/aspose.slides.charts/trendline/period/) | Określa okres linii trendu dla linii trendu średniej kroczącej. Jest ignorowane dla innych wariantów linii trendu.<br/>            Wartość musi być pomiędzy 2 a 255.<br/>            Odczyt/zapis **int**. |
| [`display_r_squared_value`](/slides/python-net/pl/aspose.slides.charts/trendline/display_r_squared_value/) | Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tej samej etykiecie co równanie).<br/>            Odczyt/zapis **bool**. |
| [`related_legend_entry`](/slides/python-net/pl/aspose.slides.charts/trendline/related_legend_entry/) | Reprezentuje pozycję legendy związaną z tą linią trendu<br/>            Tylko do odczytu [`ILegendEntryProperties`](/slides/python-net/pl/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/pl/aspose.slides.charts/trendline/text_frame_for_overriding/) | Może zawierać bogato sformatowany tekst. Jeśli ta właściwość nie jest None, to ta <br/>            sformatowana wartość tekstu nadpisuje automatycznie generowany tekst etykiety danych.<br/>            Automatycznie generowany tekst etykiety danych oznacza tekst zarządzany przez właściwości ShowSeriesName, <br/>            ShowValue, ... i formatowany właściwością TextFormatManager.TextFormat.<br/>            Tylko do odczytu [`ITextFrame`](/slides/python-net/pl/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/pl/aspose.slides.charts/trendline/text_format/) | Zwraca format tekstu.<br/>            Tylko do odczytu [`IChartTextFormat`](/slides/python-net/pl/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/trendline/chart/) | Zwraca wykres nadrzędny.<br/>            Tylko do odczytu [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/trendline/presentation/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/pl/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Inicjalizuje TextFrameForOverriding tekstem w parametrze "text".<br/>            Jeśli TextFrameForOverriding jest już zainicjalizowany, po prostu zmienia jego tekst. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)