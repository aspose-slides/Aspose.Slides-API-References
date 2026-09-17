---
title: IGeometryShape class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/igeometryshape/
---
## IGeometryShape класс

Представляет базовый класс для всех геометрических фигур.

Тип IGeometryShape предоставляет следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/ru/aspose.slides/igeometryshape/shape_style/) | Возвращает объект стиля формы.<br/>Только для чтения [`IShapeStyle`](/slides/python-net/ru/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ru/aspose.slides/igeometryshape/shape_type/) | Возвращает или задает тип предустановки геометрии.<br/>Примечание: при изменении значения все значения корректировок будут сброшены к значениям по умолчанию.<br/>Чтение/запись [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ru/aspose.slides/igeometryshape/adjustments/) | Возвращает коллекцию значений корректировок формы.<br/>Только для чтения [`IAdjustValueCollection`](/slides/python-net/ru/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ru/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/ru/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/ru/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/ru/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ru/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/ru/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/ru/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ru/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/ru/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/ru/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/ru/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/ru/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/ru/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/ru/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ru/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/ru/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/ru/aspose.slides/igeometryshape/get_geometry_paths/#) | Возвращает копию пути геометрической формы. Координаты относительно левого верхнего угла формы. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ru/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Обновляет геометрию формы из объекта [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительными к левому<br/>верхнему углу формы.<br/>Изменяет тип формы ([`IGeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/igeometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ru/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Обновляет геометрию формы из массива [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительными к левому<br/>верхнему углу формы.<br/>Изменяет тип формы ([`IGeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/igeometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ru/aspose.slides/igeometryshape/create_shape_elements/#) | Создает и возвращает массив элементов формы. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)