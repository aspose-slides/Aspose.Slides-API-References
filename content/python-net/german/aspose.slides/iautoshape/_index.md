---
title: IAutoShape class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iautoshape/
---
## IAutoShape class

Stellt ein AutoShape dar.

Der Typ IAutoShape stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`shape_lock`](/slides/python-net/de/aspose.slides/iautoshape/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur-Lesen [`IAutoShapeLock`](/slides/python-net/de/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/de/aspose.slides/iautoshape/auto_shape_lock/) | Gibt die Sperren des AutoShape zurück.<br/>            Nur-Lesen [`IAutoShapeLock`](/slides/python-net/de/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/de/aspose.slides/iautoshape/text_frame/) | Gibt das TextFrame-Objekt für das AutoShape zurück.<br/>            Nur-Lesen [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/de/aspose.slides/iautoshape/use_background_fill/) | Bestimmt, ob diese AutoShape mit dem Hintergrund der Folie gefüllt werden soll, anstatt vom Stil oder Fill-Format festgelegt zu werden.<br/>            Lesen/Schreiben **bool**. |
| [`is_text_box`](/slides/python-net/de/aspose.slides/iautoshape/is_text_box/) | Gibt an, ob die Form ein Textfeld ist. |
| [`shape_style`](/slides/python-net/de/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/de/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/de/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/de/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/de/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/de/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/de/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/de/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/de/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/de/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/de/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/de/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/de/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/de/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/de/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/de/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/de/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/de/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/de/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/de/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/de/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/de/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/de/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/de/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/de/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/de/aspose.slides/iautoshape/add_text_frame/#str) | Fügt einer Form ein neues TextFrame hinzu.<br/>            Hat die Form bereits ein TextFrame, wird einfach dessen Text geändert. |
| [`get_geometry_paths(self)`](/slides/python-net/de/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/de/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/de/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/de/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/iautoshape/get_base_placeholder/#) |  |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)