---
title: IAutoShape class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iautoshape/
---
## IAutoShape クラス

AutoShape を表します。

IAutoShape タイプは次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/iautoshape/shape_lock/) | Returns shape's locks.<br/>            読み取り専用 [`IAutoShapeLock`](/slides/python-net/ja/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/ja/aspose.slides/iautoshape/auto_shape_lock/) | Returns AutoShape's locks.<br/>            読み取り専用 [`IAutoShapeLock`](/slides/python-net/ja/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/ja/aspose.slides/iautoshape/text_frame/) | Returns TextFrame object for the AutoShape.<br/>            読み取り専用 [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/ja/aspose.slides/iautoshape/use_background_fill/) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format.<br/>            読み書き可能 **bool**. |
| [`is_text_box`](/slides/python-net/ja/aspose.slides/iautoshape/is_text_box/) | Specifies if the shape is a text box. |
| [`shape_style`](/slides/python-net/ja/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/ja/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/ja/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ja/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/ja/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/ja/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/ja/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ja/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/ja/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/ja/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ja/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/ja/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/ja/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/ja/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/ja/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/ja/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/ja/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ja/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/iautoshape/hyperlink_manager/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/ja/aspose.slides/iautoshape/add_text_frame/#str) | Adds a new TextFrame to a shape.<br/>            If shape already has TextFrame then simply changes its text. |
| [`get_geometry_paths(self)`](/slides/python-net/ja/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ja/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ja/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/ja/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/iautoshape/get_base_placeholder/#) |  |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)