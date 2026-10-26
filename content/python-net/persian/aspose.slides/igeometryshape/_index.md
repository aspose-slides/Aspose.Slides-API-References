---
title: IGeometryShape class
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/igeometryshape/
---
## IGeometryShape کلاس

نمایانگر کلاس پایه برای تمام اشکال هندسی است.

نوع IGeometryShape اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`shape_style`](/slides/python-net/fa/aspose.slides/igeometryshape/shape_style/) | شیء سبک شکل را برمی‌گرداند.<br/>            فقط خواندنی [`IShapeStyle`](/slides/python-net/fa/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fa/aspose.slides/igeometryshape/shape_type/) | نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند.<br/>            توجه: هنگام تغییر مقدار همه مقادیر تنظیم به مقادیر پیش‌فرض خود بازنشانی می‌شود.<br/>            خواندنی/نوشتنی [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fa/aspose.slides/igeometryshape/adjustments/) | مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند.<br/>            فقط خواندنی [`IAdjustValueCollection`](/slides/python-net/fa/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/fa/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/fa/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/fa/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/fa/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/fa/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/fa/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/fa/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/fa/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/fa/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/fa/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/fa/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/fa/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/fa/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/fa/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/fa/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides/igeometryshape/get_geometry_paths/#) | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالایی چپ شکل هستند. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | هندسهٔ شکل را از شیء [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالایی چپ شکل باشند.<br/>             نوع شکل ([`IGeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/igeometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | هندسهٔ شکل را از آرایهٔ [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالایی چپ شکل باشند.<br/>             نوع شکل ([`IGeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/igeometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides/igeometryshape/create_shape_elements/#) | آرایه‌ای از عناصر شکل ایجاد کرده و برمی‌گرداند. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)