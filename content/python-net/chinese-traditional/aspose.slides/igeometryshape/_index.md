---
title: IGeometryShape class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/igeometryshape/
---
## IGeometryShape 類別

表示所有幾何形狀的父類別。

IGeometryShape 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/shape_style/) | 傳回形狀的樣式物件。<br/>唯讀 [`IShapeStyle`](/slides/python-net/zh-hant/aspose.slides/ishapestyle)。 |
| [`shape_type`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/shape_type/) | 傳回或設定幾何預設類型。<br/>注意：在值變更時，所有調整值將重設為其預設值。<br/>可讀寫 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| [`adjustments`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/adjustments/) | 傳回形狀調整值的集合。<br/>唯讀 [`IAdjustValueCollection`](/slides/python-net/zh-hant/aspose.slides/iadjustvaluecollection)。 |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/get_geometry_paths/#) | 傳回幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | 從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 物件更新形狀幾何。座標必須相對於形狀的左<br/>上角。<br/>將形狀的類型 ([`IGeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | 從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀的左<br/>上角。<br/>將形狀的類型 ([`IGeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`create_shape_elements(self)`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/create_shape_elements/#) | 建立並傳回形狀元素的陣列。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)