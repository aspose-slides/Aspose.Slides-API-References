---
title: IAutoShape class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/iautoshape/
---
## IAutoShape فئة

يمثل AutoShape.

نوع IAutoShape يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/iautoshape/shape_lock/) | يُرجع أقفال الشكل.<br/>            للقراءة فقط [`IAutoShapeLock`](/slides/python-net/ar/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/ar/aspose.slides/iautoshape/auto_shape_lock/) | يعيد أقفال AutoShape.<br/>            للقراءة فقط [`IAutoShapeLock`](/slides/python-net/ar/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/ar/aspose.slides/iautoshape/text_frame/) | يعيد كائن TextFrame لـ AutoShape.<br/>            للقراءة فقط [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/ar/aspose.slides/iautoshape/use_background_fill/) | يحدد ما إذا كان يجب ملء هذا الشكل التلقائي بملء خلفية الشريحة بدلاً من المحدد بواسطة النمط أو تنسيق التعبئة.<br/>            قابل للقراءة والكتابة **bool**. |
| [`is_text_box`](/slides/python-net/ar/aspose.slides/iautoshape/is_text_box/) | يحدد ما إذا كان الشكل هو مربع نص. |
| [`shape_style`](/slides/python-net/ar/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/ar/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/ar/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ar/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/ar/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/ar/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/ar/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ar/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/ar/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/ar/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ar/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/ar/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/ar/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/ar/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/ar/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/ar/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/ar/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ar/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/ar/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/iautoshape/hyperlink_manager/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/ar/aspose.slides/iautoshape/add_text_frame/#str) | يضيف TextFrame جديدًا إلى الشكل.<br/>            إذا كان الشكل يحتوي بالفعل على TextFrame فسيتم ببساطة تغيير نصه. |
| [`get_geometry_paths(self)`](/slides/python-net/ar/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ar/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ar/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/ar/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/iautoshape/get_base_placeholder/#) |  |


### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)