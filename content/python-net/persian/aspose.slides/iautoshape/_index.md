---
title: IAutoShape class
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/iautoshape/
---
## IAutoShape کلاس

نمایانگر یک AutoShape است.

نوع IAutoShape اعضای زیر را ارائه می‌دهد:

## خصوصیات

| ویژگی | توضیح |
| :- | :- |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/iautoshape/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IAutoShapeLock`](/slides/python-net/fa/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/fa/aspose.slides/iautoshape/auto_shape_lock/) | قفل‌های AutoShape را برمی‌گرداند.<br/>            فقط‌خواندنی [`IAutoShapeLock`](/slides/python-net/fa/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/fa/aspose.slides/iautoshape/text_frame/) | شیء TextFrame مربوط به AutoShape را برمی‌گرداند.<br/>            فقط‌خواندنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/fa/aspose.slides/iautoshape/use_background_fill/) | مشخص می‌کند که آیا این autoshape باید با رنگ پس‌زمینهٔ اسلاید پر شود به جای آنکه توسط سبک یا قالب پر شدن مشخص شود.<br/>            خواندنی/نوشتنی **bool**. |
| [`is_text_box`](/slides/python-net/fa/aspose.slides/iautoshape/is_text_box/) | مشخص می‌کند که آیا شکل یک جعبهٔ متن است. |
| [`shape_style`](/slides/python-net/fa/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/fa/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/fa/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/fa/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/fa/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/fa/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/fa/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/fa/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/fa/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/fa/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/fa/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/fa/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/fa/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/fa/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/fa/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/fa/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/fa/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/fa/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/iautoshape/hyperlink_manager/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/fa/aspose.slides/iautoshape/add_text_frame/#str) | یک TextFrame جدید به یک شکل اضافه می‌کند.<br/>            اگر شکل از قبل TextFrame داشته باشد، متن آن را به سادگی تغییر می‌دهد. |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/iautoshape/get_base_placeholder/#) |  |


### همچنین ببینید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)