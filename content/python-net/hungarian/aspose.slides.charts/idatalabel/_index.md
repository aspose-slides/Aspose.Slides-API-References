---
title: IDataLabel class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabel/
---
## IDataLabel osztály

Képviseli a sorozat címkéit.

Az IDataLabel típus a következő tagokat tartalmazza:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`is_visible`](/slides/python-net/hu/aspose.slides.charts/idatalabel/is_visible/) | False means that data label is not visible (and so all Show*-flags (ShowValue, ...) are false).<br/>            Csak olvasható **bool**. |
| [`data_label_format`](/slides/python-net/hu/aspose.slides.charts/idatalabel/data_label_format/) | Visszaadja az adatcímke formátumát.<br/>            Csak olvasható [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/hu/aspose.slides.charts/idatalabel/value_from_cell/) | Lekéri vagy beállítja a munkafüzet adatcelláját. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |
| [`label_shape_type`](/slides/python-net/hu/aspose.slides.charts/idatalabel/label_shape_type/) | Lekéri vagy beállítja az adatcímke alakzattípusát.<br/>             Visszaadja [`ShapeType.NOT_DEFINED`](/slides/python-net/hu/aspose.slides/shapetype/NOT_DEFINED)-t, ha nincs definiálva alakzat. |
| [`x`](/slides/python-net/hu/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/hu/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/hu/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/hu/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/hu/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/hu/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/hu/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/hu/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/hu/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/hu/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/hu/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/hu/aspose.slides.charts/idatalabel/actual_height/) |  |

## Metódusok

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/hu/aspose.slides.charts/idatalabel/hide/#) | Make data label hidden by setting all Show*-flags (ShowValue, ...) to false state.<br/>            IsVisible will be false after this. |
| [`get_actual_label_text(self)`](/slides/python-net/hu/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/hu/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)