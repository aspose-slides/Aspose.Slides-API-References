---
title: Trendline class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/trendline/
---
## Trendline Klasse

Klasse repräsentiert die Trendlinie einer Diagrammserie

Der Trendline-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`trendline_name`](/slides/python-net/de/aspose.slides.charts/trendline/trendline_name/) | Ruft den Namen der Trendline ab oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`trendline_type`](/slides/python-net/de/aspose.slides.charts/trendline/trendline_type/) | Ruft den Typ der Trendlinie ab oder legt ihn fest.<br/>            Lesen/Schreiben [`TrendlineType`](/slides/python-net/de/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/de/aspose.slides.charts/trendline/format/) | Stellt das Format der Trendlinie dar.<br/>            Lesen/Schreiben [`IFormat`](/slides/python-net/de/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/de/aspose.slides.charts/trendline/backward/) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die die Trendlinie vor den Daten der trendenden Serie erweitert wird.<br/>            Bei Streu- und Nicht-Streu-Diagrammen muss der Wert ein nicht-negativer Wert sein.<br/>            Lesen/Schreiben **float**. |
| [`forward`](/slides/python-net/de/aspose.slides.charts/trendline/forward/) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die die Trendlinie nach den Daten der trendenden Serie erweitert wird.<br/>            Bei Streu- und Nicht-Streu-Diagrammen muss der Wert ein nicht-negativer Wert sein.<br/>            Lesen/Schreiben **float**. |
| [`intercept`](/slides/python-net/de/aspose.slides.charts/trendline/intercept/) | Gibt den Wert an, bei dem die Trendlinie die y-Achse schneidet. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist.<br/>            Lesen/Schreiben **float**. |
| [`display_equation`](/slides/python-net/de/aspose.slides.charts/trendline/display_equation/) | Gibt an, dass die Gleichung für die Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquared-Wert).<br/>            Lesen/Schreiben **bool**. |
| [`order`](/slides/python-net/de/aspose.slides.charts/trendline/order/) | Gibt die Ordnung der polynomialen Trendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 6 liegen.<br/>            Lesen/Schreiben **int**. |
| [`period`](/slides/python-net/de/aspose.slides.charts/trendline/period/) | Gibt den Zeitraum der Trendlinie für eine gleitende Durchschnittstrendlinie an. Sie wird für andere Trendlinienvarianten ignoriert. Der Wert muss zwischen 2 und 255 liegen.<br/>            Lesen/Schreiben **int**. |
| [`display_r_squared_value`](/slides/python-net/de/aspose.slides.charts/trendline/display_r_squared_value/) | Gibt an, dass der R-quadratisch-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung).<br/>            Lesen/Schreiben **bool**. |
| [`related_legend_entry`](/slides/python-net/de/aspose.slides.charts/trendline/related_legend_entry/) | Stellt den Legendeneintrag dar, der mit dieser Trendlinie verknüpft ist<br/>            Nur-lesen [`ILegendEntryProperties`](/slides/python-net/de/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/de/aspose.slides.charts/trendline/text_frame_for_overriding/) | Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht None ist, überschreibt dieser <br/>            formatierte Textwert den automatisch generierten Text des Datenlabels.<br/>            Automatisch generierter Text des Datenlabels bedeutet Text, der durch die Eigenschaften ShowSeriesName, <br/>            ShowValue, … verwaltet wird und mit der Eigenschaft TextFormatManager.TextFormat formatiert ist.<br/>            Nur-lesen [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/de/aspose.slides.charts/trendline/text_format/) | Gibt das Textformat zurück.<br/>            Nur-lesen [`IChartTextFormat`](/slides/python-net/de/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/de/aspose.slides.charts/trendline/chart/) | Gibt das übergeordnete Diagramm zurück.<br/>            Nur-lesen [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/de/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/trendline/presentation/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/de/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text".<br/>            Wenn TextFrameForOverriding bereits initialisiert ist, ändert es einfach dessen Text. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)