---
title: IConnector class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/iconnector/
---
## IConnector класс

Представляет соединитель.

Тип IConnector предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/iconnector/shape_lock/) | Возвращает блокировки фигуры.<br/>            Только чтение [`IConnectorLock`](/slides/python-net/ru/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/ru/aspose.slides/iconnector/connector_lock/) | Возвращает блокировки соединителя.<br/>            Только чтение [`IConnectorLock`](/slides/python-net/ru/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/ru/aspose.slides/iconnector/start_shape_connected_to/) | Возвращает или задает фигуру, к которой будет прикреплён начало соединителя.<br/>            Чтение/запись [`IShape`](/slides/python-net/ru/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/ru/aspose.slides/iconnector/end_shape_connected_to/) | Возвращает или задает фигуру, к которой будет прикреплён конец соединителя.<br/>            Чтение/запись [`IShape`](/slides/python-net/ru/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/ru/aspose.slides/iconnector/start_shape_connection_site_index/) | Возвращает или задает индекс точки подключения для начальной фигуры.<br/>            Чтение/запись **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/ru/aspose.slides/iconnector/end_shape_connection_site_index/) | Возвращает или задает индекс точки подключения для конечной фигуры.<br/>            Чтение/запись **int**. |
| [`shape_style`](/slides/python-net/ru/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/ru/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/ru/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ru/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/ru/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/ru/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/ru/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ru/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/ru/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/ru/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ru/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/ru/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/ru/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/ru/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/ru/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/ru/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/ru/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ru/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/ru/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/iconnector/hyperlink_manager/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/ru/aspose.slides/iconnector/reroute/#) | Перенаправляет соединитель так, чтобы он выбирал кратчайший возможный путь между соединяемыми фигурами. |
| [`get_geometry_paths(self)`](/slides/python-net/ru/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ru/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ru/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/ru/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/iconnector/get_base_placeholder/#) |  |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)