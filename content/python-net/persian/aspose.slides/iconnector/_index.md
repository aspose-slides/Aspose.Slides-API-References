---
title: IConnector class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/iconnector/
---
## IConnector کلاس

یک کانکتور را نشان می‌دهد.

نوع IConnector اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/iconnector/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IConnectorLock`](/slides/python-net/fa/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/fa/aspose.slides/iconnector/connector_lock/) | قفل‌های Connector را برمی‌گرداند.<br/>            فقط-خواندنی [`IConnectorLock`](/slides/python-net/fa/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/fa/aspose.slides/iconnector/start_shape_connected_to/) | شکل متصل به ابتدای connector را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IShape`](/slides/python-net/fa/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/fa/aspose.slides/iconnector/end_shape_connected_to/) | شکل متصل به انتهای connector را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IShape`](/slides/python-net/fa/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/fa/aspose.slides/iconnector/start_shape_connection_site_index/) | اندیس محل اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/fa/aspose.slides/iconnector/end_shape_connection_site_index/) | اندیس محل اتصال برای شکل پایان را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`shape_style`](/slides/python-net/fa/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/fa/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/fa/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/fa/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/fa/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/fa/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/fa/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/fa/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/fa/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/fa/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/fa/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/fa/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/fa/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/fa/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/fa/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/fa/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/fa/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/fa/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/iconnector/hyperlink_manager/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/fa/aspose.slides/iconnector/reroute/#) | مسیر connector را بازسازی می‌کند تا کوتاه‌ترین مسیر ممکن بین اشکالی که به هم متصل می‌کند را اتخاذ کند. |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/iconnector/get_base_placeholder/#) |  |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)