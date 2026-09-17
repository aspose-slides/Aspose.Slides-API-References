---
title: ChartTitle class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/charttitle/
---
## ChartTitle Klasse

Stellt die Eigenschaften des Diagrammtitels dar.

Der ChartTitle-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/de/aspose.slides.charts/charttitle/x/) | Gibt die x-Koordinate eines Titels als Bruchteil der Breite des Diagramms zurück oder legt sie fest.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/de/aspose.slides.charts/charttitle/y/) | Gibt die y-Koordinate eines Titels als Bruchteil der Höhe des Diagramms zurück oder legt sie fest.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/de/aspose.slides.charts/charttitle/width/) | Gibt die Breite eines Titels als Bruchteil der Breite des Diagramms zurück oder legt sie fest.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/de/aspose.slides.charts/charttitle/height/) | Gibt die Höhe eines Titels als Bruchteil der Höhe des Diagramms zurück oder legt sie fest.<br/>            Read/write **float**. |
| [`right`](/slides/python-net/de/aspose.slides.charts/charttitle/right/) | Rechts.<br/>            Read-only **float**. |
| [`bottom`](/slides/python-net/de/aspose.slides.charts/charttitle/bottom/) | Unten.<br/>            Read-only **float**. |
| [`overlay`](/slides/python-net/de/aspose.slides.charts/charttitle/overlay/) | Bestimmt, ob andere Diagrammelemente den Titel überlappen dürfen.<br/>            Read/write **bool**. |
| [`format`](/slides/python-net/de/aspose.slides.charts/charttitle/format/) | Gibt die Füll-, Linien- und Effekts-Stile eines Titels zurück.<br/>            Read-only [`IFormat`](/slides/python-net/de/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/de/aspose.slides.charts/charttitle/text_frame_for_overriding/) | Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht None ist, überschreibt dieser formatierte Textwert den automatisch generierten Text.<br/>            Der automatisch generierte Text ist eine implizite Eigenschaft des Datenlabels, der Anzeige-Einheitsbeschriftung der Werteachse, des Achsentitels, des Diagrammtitels, der Beschriftung der Trendlinie.<br/>            Der automatisch generierte Text wird mit der IFormattedTextContainer.TextFormat-Eigenschaft formatiert.<br/>            Read-only [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/de/aspose.slides.charts/charttitle/text_format/) | Gibt das Textformat zurück.<br/>            Read-only [`IChartTextFormat`](/slides/python-net/de/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/de/aspose.slides.charts/charttitle/actual_x/) | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an.<br/>            Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. <br/>            Read **float**. |
| [`actual_y`](/slides/python-net/de/aspose.slides.charts/charttitle/actual_y/) | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an.<br/>            Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. <br/>            Read **float**. |
| [`actual_width`](/slides/python-net/de/aspose.slides.charts/charttitle/actual_width/) | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. <br/>            Read **float**. |
| [`actual_height`](/slides/python-net/de/aspose.slides.charts/charttitle/actual_height/) | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. <br/>            Read **float**. |
| [`chart`](/slides/python-net/de/aspose.slides.charts/charttitle/chart/) | Gibt das übergeordnete Diagramm zurück.<br/>            Read-only [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/de/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/charttitle/presentation/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/de/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text".<br/>            Wenn TextFrameForOverriding bereits initialisiert ist, wird einfach sein Text geändert. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)