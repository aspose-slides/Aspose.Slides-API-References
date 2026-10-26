---
title: IAutoShape class
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/iautoshape/
---
## IAutoShape třída

Představuje AutoShape.

Typ IAutoShape vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/iautoshape/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IAutoShapeLock`](/slides/python-net/cs/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/cs/aspose.slides/iautoshape/auto_shape_lock/) | Vrací zámky AutoShape.<br/>            Pouze pro čtení [`IAutoShapeLock`](/slides/python-net/cs/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/cs/aspose.slides/iautoshape/text_frame/) | Vrací objekt TextFrame pro AutoShape.<br/>            Pouze pro čtení [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/cs/aspose.slides/iautoshape/use_background_fill/) | Určuje, zda má být tento autoshape vyplněn pozadím snímku namísto stylu nebo formátu výplně.<br/>            Čtení/Zápis **bool**. |
| [`is_text_box`](/slides/python-net/cs/aspose.slides/iautoshape/is_text_box/) | Určuje, zda je tvar textovým polem. |
| [`shape_style`](/slides/python-net/cs/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/cs/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/cs/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/cs/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/cs/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/cs/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/cs/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/cs/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/cs/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/cs/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/cs/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/cs/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/cs/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/cs/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/cs/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/cs/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/cs/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/cs/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/cs/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/cs/aspose.slides/iautoshape/add_text_frame/#str) | Přidá nový TextFrame do tvaru.<br/>            Pokud má tvar již TextFrame, jednoduše změní jeho text. |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/iautoshape/get_base_placeholder/#) |  |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)