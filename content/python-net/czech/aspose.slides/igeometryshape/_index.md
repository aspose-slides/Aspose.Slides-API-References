---
title: IGeometryShape class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/igeometryshape/
---
## IGeometryShape třída

Představuje rodičovskou třídu pro všechny geometrické tvary.

Typ IGeometryShape vystavuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/cs/aspose.slides/igeometryshape/shape_style/) | Vrací objekt stylu tvaru.<br/>            Read-only [`IShapeStyle`](/slides/python-net/cs/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/cs/aspose.slides/igeometryshape/shape_type/) | Vrací nebo nastavuje předdefinovaný typ geometrie.<br/>            Note: on value changing all adjustment values will reset to their default values.<br/>            Read/write [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/cs/aspose.slides/igeometryshape/adjustments/) | Vrací kolekci hodnot úprav tvaru.<br/>            Read-only [`IAdjustValueCollection`](/slides/python-net/cs/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/cs/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/cs/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/cs/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/cs/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/cs/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/cs/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/cs/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/cs/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/cs/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/cs/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/cs/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/cs/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/cs/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/cs/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/cs/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/cs/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/igeometryshape/get_geometry_paths/#) | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>            top corner of the shape.<br/>            Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/igeometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>            top corner of the shape.<br/>            Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/igeometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/igeometryshape/create_shape_elements/#) | Vytvoří a vrátí pole prvků tvaru. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### See Also
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)