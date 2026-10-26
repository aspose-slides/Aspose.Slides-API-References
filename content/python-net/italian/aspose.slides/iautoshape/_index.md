---
title: IAutoShape class
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/iautoshape/
---
## IAutoShape classe

Rappresenta un AutoShape.

Il tipo IAutoShape espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/it/aspose.slides/iautoshape/shape_lock/) | Restituisce i blocchi della forma.<br/>            Sola lettura [`IAutoShapeLock`](/slides/python-net/it/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/it/aspose.slides/iautoshape/auto_shape_lock/) | Restituisce i blocchi dell'AutoShape.<br/>            Sola lettura [`IAutoShapeLock`](/slides/python-net/it/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/it/aspose.slides/iautoshape/text_frame/) | Restituisce l'oggetto TextFrame per l'AutoShape.<br/>            Sola lettura [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/it/aspose.slides/iautoshape/use_background_fill/) | Determina se questo autoshape deve essere riempito con lo sfondo della diapositiva anziché con quello specificato dallo stile o dal formato di riempimento.<br/>            Lettura/scrittura **bool**. |
| [`is_text_box`](/slides/python-net/it/aspose.slides/iautoshape/is_text_box/) | Specifica se la forma è una casella di testo. |
| [`shape_style`](/slides/python-net/it/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/it/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/it/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/it/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/it/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/it/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/it/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/it/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/it/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/it/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/it/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/it/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/it/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/it/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/it/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/it/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/it/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/it/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/it/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/it/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/it/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/it/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/it/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/it/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/it/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/it/aspose.slides/iautoshape/add_text_frame/#str) | Aggiunge un nuovo TextFrame a una forma.<br/>            Se la forma ha già un TextFrame, cambia semplicemente il suo testo. |
| [`get_geometry_paths(self)`](/slides/python-net/it/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/it/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/it/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/it/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/iautoshape/get_base_placeholder/#) |  |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)