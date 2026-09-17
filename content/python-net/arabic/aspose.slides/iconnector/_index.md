---
title: IConnector class
second_title: دليل مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/iconnector/
---
## IConnector فئة

يمثل موصلاً.

يعرض نوع IConnector الأعضاء التالية:

## خصائص

| خاصية | الوصف |
| :- | :- |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/iconnector/shape_lock/) | Returns shape's locks.<br/>            للقراءة فقط [`IConnectorLock`](/slides/python-net/ar/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/ar/aspose.slides/iconnector/connector_lock/) | Returns Connector's locks.<br/>            للقراءة فقط [`IConnectorLock`](/slides/python-net/ar/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/ar/aspose.slides/iconnector/start_shape_connected_to/) | Returns or sets the shape to attach the beginning of the connector to.<br/>            قراءة/كتابة [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/ar/aspose.slides/iconnector/end_shape_connected_to/) | Returns or sets the shape to attach the end of the connector to.<br/>            قراءة/كتابة [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/ar/aspose.slides/iconnector/start_shape_connection_site_index/) | Returns or sets the index of connection site for start shape.<br/>            قراءة/كتابة **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/ar/aspose.slides/iconnector/end_shape_connection_site_index/) | Returns or sets the index of connection site for end shape.<br/>            قراءة/كتابة **int**. |
| [`shape_style`](/slides/python-net/ar/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/ar/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/ar/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ar/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/ar/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/ar/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/ar/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ar/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/ar/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/ar/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ar/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/ar/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/ar/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/ar/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/ar/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/ar/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/ar/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ar/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/ar/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/iconnector/hyperlink_manager/) |  |

## طرق

| طريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/ar/aspose.slides/iconnector/reroute/#) | يعيد توجيه الموصل بحيث يأخذ أقصر مسار ممكن بين الأشكال التي يربطها. |
| [`get_geometry_paths(self)`](/slides/python-net/ar/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ar/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ar/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/ar/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/iconnector/get_base_placeholder/#) |  |

### انظر أيضًا
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)