---
title: DataLabel class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabel/
---
## DataLabel Klasse

Stellt die Serienbeschriftungen dar.

Der DataLabel-Typ stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/de/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Erstellt eine neue Instanz der DataLabel-Klasse. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`chart`](/slides/python-net/de/aspose.slides.charts/datalabel/chart/) | Gibt das übergeordnete Diagramm zurück.<br/>            Nur-Lesen [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/de/aspose.slides.charts/datalabel/is_visible/) | False bedeutet, dass das Datenlabel nicht sichtbar ist (und somit alle Show*-Flags (ShowValue, ...) false sind).<br/>            Nur-Lesen **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/de/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht None ist, dann überschreibt dieser <br/>            formatierte Textwert den automatisch erzeugten Text des Datenlabels.<br/>            Der automatisch erzeugte Text des Datenlabels bedeutet Text, der von den Eigenschaften ShowSeriesName, <br/>            ShowValue, ... verwaltet wird und mit der Eigenschaft TextFormatManager.TextFormat formatiert ist.<br/>            Nur-Lesen [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/de/aspose.slides.charts/datalabel/text_format/) | Gibt Textformat zurück.<br/>            Nur-Lesen [`IChartTextFormat`](/slides/python-net/de/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/de/aspose.slides.charts/datalabel/x/) | Gibt die x-Koordinate eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides.charts/datalabel/y/) | Gibt die y-Koordinate eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides.charts/datalabel/width/) | Gibt die Breite eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides.charts/datalabel/height/) | Gibt die Höhe eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie.<br/>            Lesen/Schreiben **float**. |
| [`right`](/slides/python-net/de/aspose.slides.charts/datalabel/right/) | Rechts.<br/>            Nur-Lesen **float**. |
| [`bottom`](/slides/python-net/de/aspose.slides.charts/datalabel/bottom/) | Unten.<br/>            Nur-Lesen **float**. |
| [`data_label_format`](/slides/python-net/de/aspose.slides.charts/datalabel/data_label_format/) | Gibt das Datenlabel-Format zurück.<br/>            Nur-Lesen [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/de/aspose.slides.charts/datalabel/value_from_cell/) | Liest oder setzt die Arbeitsblatt-Datenzelle. Wird angewandt, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell true ist. |
| [`actual_x`](/slides/python-net/de/aspose.slides.charts/datalabel/actual_x/) | Gibt den tatsächlichen x-Standort (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an.<br/>            Rufe die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten.<br/>            Lesen **float**. |
| [`actual_y`](/slides/python-net/de/aspose.slides.charts/datalabel/actual_y/) | Gibt den tatsächlichen oberen Rand des Diagrammelements relativ zur linken oberen Ecke des Diagramms an.<br/>            Rufe die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten.<br/>            Lesen **float**. |
| [`actual_width`](/slides/python-net/de/aspose.slides.charts/datalabel/actual_width/) | Gibt die tatsächliche Breite des Diagrammelements an. Rufe die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten.<br/>            Lesen **float**. |
| [`actual_height`](/slides/python-net/de/aspose.slides.charts/datalabel/actual_height/) | Gibt die tatsächliche Höhe des Diagrammelements an. Rufe die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten.<br/>            Lesen **float**. |
| [`slide`](/slides/python-net/de/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/datalabel/presentation/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`hide(self)`](/slides/python-net/de/aspose.slides.charts/datalabel/hide/#) | Macht das Datenlabel unsichtbar, indem alle Show*-Flags (ShowValue, ...) auf den falschen Zustand gesetzt werden.<br/>            IsVisible wird danach false sein. |
| [`get_actual_label_text(self)`](/slides/python-net/de/aspose.slides.charts/datalabel/get_actual_label_text/#) | Gibt den tatsächlichen Beschriftungstext zurück, basierend auf den Einstellungen von DataLabelFormat oder dem Wert von TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/de/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text".<br/>            Wenn TextFrameForOverriding bereits initialisiert ist, ändert es einfach dessen Text. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)