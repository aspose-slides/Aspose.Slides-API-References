---
title: IDataLabel class
second_title: Aspose.Slides para Python mediante .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/idatalabel/
---
## IDataLabel clase

Representa etiquetas de serie.

El tipo IDataLabel expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_visible`](/slides/python-net/es/aspose.slides.charts/idatalabel/is_visible/) | False significa que la etiqueta de datos no es visible (y por lo tanto todas las banderas Show*-flags (ShowValue, ...) son false).<br/>            Solo lectura **bool**. |
| [`data_label_format`](/slides/python-net/es/aspose.slides.charts/idatalabel/data_label_format/) | Devuelve el formato de la etiqueta de datos.<br/>            Solo lectura [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/es/aspose.slides.charts/idatalabel/value_from_cell/) | Obtiene o establece la celda de datos del libro. Se aplica si la propiedad IDataLabelFormat.ShowLabelValueFromCell es true. |
| [`x`](/slides/python-net/es/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/es/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/es/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/es/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/es/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/es/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/es/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/es/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/es/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/es/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/es/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/es/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/es/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/es/aspose.slides.charts/idatalabel/actual_height/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`hide(self)`](/slides/python-net/es/aspose.slides.charts/idatalabel/hide/#) | Oculta la etiqueta de datos estableciendo todas las banderas Show*-flags (ShowValue, ...) en estado false.<br/>            IsVisible será false después de esto. |
| [`get_actual_label_text(self)`](/slides/python-net/es/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Devuelve el texto real de la etiqueta basado en la configuración de DataLabelFormat o el valor TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/es/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)