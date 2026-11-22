---
title: DataLabel class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabel/
---
## DataLabel Klasse

Stellt Serienbeschriftungen dar.

Der DataLabel-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Constructor | Description |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/de/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Erstellt eine neue Instanz der DataLabel Klasse. |

## Eigenschaften

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/de/aspose.slides.charts/datalabel/chart/) | Gibt das übergeordnete Diagramm zurück.<br/>            Nur lesend [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/de/aspose.slides.charts/datalabel/is_visible/) | False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) false sind).<br/>            Nur lesend **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/de/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht None ist, überschreibt dieser <br/>            formatierte Textwert den automatisch erzeugten Text der Datenbeschriftung.<br/>            Der automatisch erzeugte Text der Datenbeschriftung bedeutet Text, der von den Eigenschaften ShowSeriesName, <br/>            ShowValue, ... verwaltet wird und mit der Eigenschaft TextFormatManager.TextFormat formatiert ist.<br/>            Nur lesend [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/de/aspose.slides.charts/datalabel/text_format/) | Gibt das Textformat zurück.<br/>            Nur lesend [`IChartTextFormat`](/slides/python-net/de/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/de/aspose.slides.charts/datalabel/x/) | Liest oder setzt die x-Koordinate eines Titels als Bruchteil der Diagrammbreite.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides.charts/datalabel/y/) | Liest oder setzt die y-Koordinate eines Titels als Bruchteil der Diagrammhöhe.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides.charts/datalabel/width/) | Liest oder setzt die Breite eines Titels als Bruchteil der Diagrammbreite.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides.charts/datalabel/height/) | Liest oder setzt die Höhe eines Titels als Bruchteil der Diagrammhöhe.<br/>            Lesen/Schreiben **float**. |
| [`right`](/slides/python-net/de/aspose.slides.charts/datalabel/right/) | Rechts.<br/>            Nur lesend **float**. |
| [`bottom`](/slides/python-net/de/aspose.slides.charts/datalabel/bottom/) | Unten.<br/>            Nur lesend **float**. |
| [`data_label_format`](/slides/python-net/de/aspose.slides.charts/datalabel/data_label_format/) | Gibt das Datenbeschriftungsformat zurück.<br/>            Nur lesend [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/de/aspose.slides.charts/datalabel/value_from_cell/) | Liest oder setzt die Arbeitsmappen-Datenzelle. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell true ist. |
| [`label_shape_type`](/slides/python-net/de/aspose.slides.charts/datalabel/label_shape_type/) | Liest oder setzt den Formtyp der Datenbeschriftung.<br/>             Gibt [`ShapeType.NOT_DEFINED`](/slides/python-net/de/aspose.slides/shapetype/NOT_DEFINED) zurück, wenn keine Form definiert ist. |
| [`actual_x`](/slides/python-net/de/aspose.slides.charts/datalabel/actual_x/) | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an.<br/>            Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Lesen **float**. |
| [`actual_y`](/slides/python-net/de/aspose.slides.charts/datalabel/actual_y/) | Gibt die tatsächliche Oberkante des Diagrammelements relativ zur linken oberen Ecke des Diagramms an.<br/>            Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Lesen **float**. |
| [`actual_width`](/slides/python-net/de/aspose.slides.charts/datalabel/actual_width/) | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Lesen **float**. |
| [`actual_height`](/slides/python-net/de/aspose.slides.charts/datalabel/actual_height/) | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Lesen **float**. |
| [`slide`](/slides/python-net/de/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/datalabel/presentation/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/de/aspose.slides.charts/datalabel/hide/#) | Macht die Datenbeschriftung verborgen, indem alle Show*-Flags (ShowValue, ...) auf den falschen Zustand gesetzt werden.<br/>            IsVisible wird danach false sein. |
| [`get_actual_label_text(self)`](/slides/python-net/de/aspose.slides.charts/datalabel/get_actual_label_text/#) | Gibt den tatsächlichen Beschriftungstext basierend auf den DataLabelFormat-Einstellungen oder dem Wert TextFrameForOverriding.Text zurück. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/de/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text".<br/>            Wenn TextFrameForOverriding bereits initialisiert ist, ändert er nur seinen Text. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)