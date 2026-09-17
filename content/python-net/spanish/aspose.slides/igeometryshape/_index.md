---
title: IGeometryShape class
second_title: Aspose.Slides para Python mediante .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/igeometryshape/
---
## IGeometryShape clase

Representa la clase base para todas las formas geométricas.

El tipo IGeometryShape expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`shape_style`](/slides/python-net/es/aspose.slides/igeometryshape/shape_style/) | Devuelve el objeto de estilo de la forma.<br/>            Solo lectura [`IShapeStyle`](/slides/python-net/es/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/es/aspose.slides/igeometryshape/shape_type/) | Devuelve o establece el tipo predefinido de geometría.<br/>            Nota: al cambiar el valor, todos los valores de ajuste se restablecerán a sus valores predeterminados.<br/>            Lectura/escritura [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/es/aspose.slides/igeometryshape/adjustments/) | Devuelve una colección de valores de ajuste de la forma.<br/>            Solo lectura [`IAdjustValueCollection`](/slides/python-net/es/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/es/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/es/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/es/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/es/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/es/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/es/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/es/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/es/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/es/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/es/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/es/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/es/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/es/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/es/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/es/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/es/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/es/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/es/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/es/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/es/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/es/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/es/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/es/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/es/aspose.slides/igeometryshape/get_geometry_paths/#) | Devuelve una copia de la ruta de la forma geométrica. Las coordenadas son relativas a la esquina superior izquierda de la forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/es/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Actualiza la geometría de la forma a partir del objeto [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma.<br/>             Cambia el tipo de la forma ([`IGeometryShape.shape_type`](/slides/python-net/es/aspose.slides/igeometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/es/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Actualiza la geometría de la forma a partir de una matriz de [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma.<br/>             Cambia el tipo de la forma ([`IGeometryShape.shape_type`](/slides/python-net/es/aspose.slides/igeometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/es/aspose.slides/igeometryshape/create_shape_elements/#) | Crea y devuelve una matriz de los elementos de la forma. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)