---
title: IDataLabel class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabel/
---
## IDataLabel klass

Representerar en serietikett.

Typen IDataLabel exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_visible`](/slides/python-net/sv/aspose.slides.charts/idatalabel/is_visible/) | False betyder att dataetiketten inte är synlig (och därför är alla Show*-flaggor (ShowValue, ...) falska).<br/>            Skrivskyddad **bool**. |
| [`data_label_format`](/slides/python-net/sv/aspose.slides.charts/idatalabel/data_label_format/) | Returnerar formatet för dataetiketten.<br/>            Skrivskyddad [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/sv/aspose.slides.charts/idatalabel/value_from_cell/) | Hämtar eller anger arbetsbokens datacell. Tillämpas om egenskapen IDataLabelFormat.ShowLabelValueFromCell är sann. |
| [`x`](/slides/python-net/sv/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/sv/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/sv/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/sv/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/sv/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/sv/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/sv/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/sv/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/sv/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/sv/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/sv/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/sv/aspose.slides.charts/idatalabel/actual_height/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`hide(self)`](/slides/python-net/sv/aspose.slides.charts/idatalabel/hide/#) | Gör dataetiketten dold genom att sätta alla Show*-flaggor (ShowValue, ...) till falskt tillstånd.<br/>            IsVisible blir falskt efter detta. |
| [`get_actual_label_text(self)`](/slides/python-net/sv/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Returnerar den faktiska etiketttexten baserat på inställningarna i DataLabelFormat eller värdet i TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/sv/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### Se också
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)