---
title: IDataLabel class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabel/
---
## IDataLabel Klasse

Stellt die Beschriftungen einer Serie dar.

Der IDataLabel-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_visible`](/slides/python-net/de/aspose.slides.charts/idatalabel/is_visible/) | False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und somit alle Show*-Flags (ShowValue, ...) false sind).<br/>            Nur lesbar **bool**. |
| [`data_label_format`](/slides/python-net/de/aspose.slides.charts/idatalabel/data_label_format/) | Gibt das Format der Datenbeschriftung zurück.<br/>            Nur lesbar [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/de/aspose.slides.charts/idatalabel/value_from_cell/) | Liest oder setzt die Arbeitsmappen-Datenzelle. Gilt, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell den Wert true hat. |
| [`label_shape_type`](/slides/python-net/de/aspose.slides.charts/idatalabel/label_shape_type/) | Liest oder setzt den Shape-Typ der Datenbeschriftung.<br/>             Gibt [`ShapeType.NOT_DEFINED`](/slides/python-net/de/aspose.slides/shapetype/NOT_DEFINED) zurück, wenn keine Form definiert ist. |
| [`x`](/slides/python-net/de/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/de/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/de/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/de/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/de/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/de/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/de/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/de/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/de/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/de/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/de/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/de/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/de/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/de/aspose.slides.charts/idatalabel/actual_height/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`hide(self)`](/slides/python-net/de/aspose.slides.charts/idatalabel/hide/#) | Macht die Datenbeschriftung unsichtbar, indem alle Show*-Flags (ShowValue, ...) auf den falschen Zustand gesetzt werden.<br/>            IsVisible wird danach false sein. |
| [`get_actual_label_text(self)`](/slides/python-net/de/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Gibt den tatsächlichen Beschriftungstext basierend auf den Einstellungen von DataLabelFormat oder dem Wert TextFrameForOverriding.Text zurück. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/de/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)