---
title: IAutoShape class
second_title: Aspose.Slides 用於 Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iautoshape/
---
## IAutoShape 類別

代表一個 AutoShape。

IAutoShape 類型公開下列成員：

## 屬性

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/iautoshape/shape_lock/) | 返回形狀的鎖定。<br/>            唯讀 [`IAutoShapeLock`](/slides/python-net/zh-hant/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/zh-hant/aspose.slides/iautoshape/auto_shape_lock/) | 返回 AutoShape 的鎖定。<br/>            唯讀 [`IAutoShapeLock`](/slides/python-net/zh-hant/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/zh-hant/aspose.slides/iautoshape/text_frame/) | 返回 AutoShape 的 TextFrame 物件。<br/>            唯讀 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/zh-hant/aspose.slides/iautoshape/use_background_fill/) | 確定此自動形狀是否應使用投影片的背景填充，而不是樣式或填充格式指定的。<br/>            可讀寫 **bool**. |
| [`is_text_box`](/slides/python-net/zh-hant/aspose.slides/iautoshape/is_text_box/) | 指定形狀是否為文字方塊。 |
| [`shape_style`](/slides/python-net/zh-hant/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/zh-hant/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/zh-hant/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/zh-hant/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/zh-hant/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/zh-hant/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/zh-hant/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/zh-hant/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/iautoshape/hyperlink_manager/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/add_text_frame/#str) | 向形狀新增一個 TextFrame。<br/>            如果形狀已經有 TextFrame，則僅變更其文字。 |
| [`get_geometry_paths(self)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/iautoshape/get_base_placeholder/#) |  |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)