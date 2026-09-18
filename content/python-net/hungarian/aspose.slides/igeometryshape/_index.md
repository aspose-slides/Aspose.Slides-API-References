---
title: IGeometryShape class
second_title: Aspose.Slides a .NET API-n keresztül a Pythonhoz Referencia
description: 
type: docs
url: /hu/aspose.slides/igeometryshape/
---
## IGeometryShape osztály

Az összes geometriai alakzat szülőosztályát képviseli.

Az IGeometryShape típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/hu/aspose.slides/igeometryshape/shape_style/) | Visszaadja az alakzat stílusobjektumát.<br/>            Csak olvasható [`IShapeStyle`](/slides/python-net/hu/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/hu/aspose.slides/igeometryshape/shape_type/) | Visszaadja vagy beállítja a geometriai előre beállított típust.<br/>            Megjegyzés: az érték megváltoztatásakor az összes igazítási érték visszaáll az alapértelmezett értékre.<br/>            Olvasható/írható [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/hu/aspose.slides/igeometryshape/adjustments/) | Visszaad egy gyűjteményt az alakzat igazítási értékeiről.<br/>            Csak olvasható [`IAdjustValueCollection`](/slides/python-net/hu/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/hu/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/hu/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/hu/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/hu/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/hu/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/hu/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/hu/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/hu/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/hu/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/hu/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/hu/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/hu/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/hu/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/hu/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/hu/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/hu/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Módszerek

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/hu/aspose.slides/igeometryshape/get_geometry_paths/#) | Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához viszonyítva vannak. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hu/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Frissíti az alakzat geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) objektumból. A koordinátáknak az alakzat bal<br/>             felső sarkához kell viszonyulniuk.<br/>             Megváltoztatja az alakzat típusát ([`IGeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/igeometryshape/shape_type)) erre: [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hu/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Frissíti az alakzat geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) tömbből. A koordinátáknak az alakzat bal<br/>             felső sarkához kell viszonyulniuk.<br/>             Megváltoztatja az alakzat típusát ([`IGeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/igeometryshape/shape_type)) erre: [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/hu/aspose.slides/igeometryshape/create_shape_elements/#) | Létrehozza és visszaadja az alakzat elemeinek tömbjét. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)