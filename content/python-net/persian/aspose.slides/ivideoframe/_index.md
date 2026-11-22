---
title: IVideoFrame class
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ivideoframe/
---
## IVideoFrame کلاس

یک کلیپ ویدئویی را بر روی اسلاید نشان می‌دهد.

نوع IVideoFrame اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`rewind_video`](/slides/python-net/fa/aspose.slides/ivideoframe/rewind_video/) | تعیین می‌کند آیا ویدئو به‌صورت خودکار بازگردانده شود تا به شروع<br/>            به محض اینکه فیلم پخش شد.<br/>            خواندنی/نوشتنی **bool**. |
| [`play_loop_mode`](/slides/python-net/fa/aspose.slides/ivideoframe/play_loop_mode/) | تعیین می‌کند آیا ویدئو به‌صورت حلقه‌ای پخش می‌شود.<br/>            خواندنی/نوشتنی **bool**. |
| [`hide_at_showing`](/slides/python-net/fa/aspose.slides/ivideoframe/hide_at_showing/) | تعیین می‌کند آیا VideoFrame مخفی باشد.<br/>            خواندنی/نوشتنی **bool**. |
| [`volume`](/slides/python-net/fa/aspose.slides/ivideoframe/volume/) | مقدار یا تنظیم حجم صدا.<br/>            خواندنی/نوشتنی [`AudioVolumeMode`](/slides/python-net/fa/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/fa/aspose.slides/ivideoframe/volume_value/) | مقدار یا تنظیم دقیق حجم ویدئو به‌صورت درصد.<br/>             مقدار به‌صورت درصد از ۰ تا ۱۰۰ بیان می‌شود. از این ویژگی برای خواندن یا تنظیم مقادیر حجمی که دقیق‌تر از سطوح پیش‌تعریف‌شدهٔ موجود از طریق ویژگی [`IVideoFrame.volume`](/slides/python-net/fa/aspose.slides/ivideoframe/volume) هستند، استفاده کنید.<br/>             خواندنی/نوشتنی **float**. |
| [`play_mode`](/slides/python-net/fa/aspose.slides/ivideoframe/play_mode/) | مقدار یا تنظیم حالت پخش ویدئو.<br/>            خواندنی/نوشتنی [`VideoPlayModePreset`](/slides/python-net/fa/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/fa/aspose.slides/ivideoframe/full_screen_mode/) | تعیین می‌کند آیا ویدئو در حالت تمام‌صفحه نمایش داده شود.<br/>            خواندنی/نوشتنی **bool**. |
| [`link_path_long`](/slides/python-net/fa/aspose.slides/ivideoframe/link_path_long/) | مقدار یا تنظیم نام فایل ویدئویی که به یک VideoFrame مرتبط است.<br/>            خواندنی/نوشتنی **str**. |
| [`embedded_video`](/slides/python-net/fa/aspose.slides/ivideoframe/embedded_video/) | مقدار یا تنظیم شیء ویدئوی توکار.<br/>            خواندنی/نوشتنی [`IVideo`](/slides/python-net/fa/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/fa/aspose.slides/ivideoframe/trim_from_start/) | مدت برش شروع [ms] |
| [`trim_from_end`](/slides/python-net/fa/aspose.slides/ivideoframe/trim_from_end/) | مدت برش پایان [ms] |
| [`caption_tracks`](/slides/python-net/fa/aspose.slides/ivideoframe/caption_tracks/) | مجموعهٔ زیرنویس‌های بسته‌ شده مرتبط با فریم صوتی را دریافت می‌کند.<br/>             این ویژگی فقط-خواندنی است و یک [`ICaptionsCollection`](/slides/python-net/fa/aspose.slides/icaptionscollection) شامل تمام مسیرهای زیرنویس برمی‌گرداند. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/ivideoframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/fa/aspose.slides/ivideoframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/fa/aspose.slides/ivideoframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/fa/aspose.slides/ivideoframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/fa/aspose.slides/ivideoframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/fa/aspose.slides/ivideoframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/fa/aspose.slides/ivideoframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/fa/aspose.slides/ivideoframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/ivideoframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/fa/aspose.slides/ivideoframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/fa/aspose.slides/ivideoframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/ivideoframe/raw_frame/) |  |
| [`frame`](/slides/python-net/fa/aspose.slides/ivideoframe/frame/) |  |
| [`line_format`](/slides/python-net/fa/aspose.slides/ivideoframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/ivideoframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/fa/aspose.slides/ivideoframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/fa/aspose.slides/ivideoframe/fill_format/) |  |
| [`hidden`](/slides/python-net/fa/aspose.slides/ivideoframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/ivideoframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/ivideoframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/fa/aspose.slides/ivideoframe/rotation/) |  |
| [`x`](/slides/python-net/fa/aspose.slides/ivideoframe/x/) |  |
| [`y`](/slides/python-net/fa/aspose.slides/ivideoframe/y/) |  |
| [`width`](/slides/python-net/fa/aspose.slides/ivideoframe/width/) |  |
| [`height`](/slides/python-net/fa/aspose.slides/ivideoframe/height/) |  |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/ivideoframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/ivideoframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/fa/aspose.slides/ivideoframe/name/) |  |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/ivideoframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/fa/aspose.slides/ivideoframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/ivideoframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/ivideoframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/ivideoframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/fa/aspose.slides/ivideoframe/parent_group/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides/ivideoframe/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/ivideoframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/ivideoframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/ivideoframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/ivideoframe/hyperlink_manager/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/ivideoframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/ivideoframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/ivideoframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/ivideoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides/ivideoframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides/ivideoframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides/ivideoframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides/ivideoframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/ivideoframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/ivideoframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/ivideoframe/get_base_placeholder/#) |  |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)