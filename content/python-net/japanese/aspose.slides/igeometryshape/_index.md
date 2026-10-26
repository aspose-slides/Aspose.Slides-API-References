---
title: IGeometryShape class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/igeometryshape/
---
## IGeometryShape クラス

Represents the parent class for all geometric shapes.

The IGeometryShape type exposes the following members:

## プロパティ

| Property | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/ja/aspose.slides/igeometryshape/shape_style/) | シェイプのスタイルオブジェクトを返します。<br/>            読み取り専用 [`IShapeStyle`](/slides/python-net/ja/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ja/aspose.slides/igeometryshape/shape_type/) | ジオメトリのプリセットタイプを取得または設定します。<br/>            注: 値を変更すると、すべての調整値がデフォルト値にリセットされます。<br/>            読み取り/書き込み [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ja/aspose.slides/igeometryshape/adjustments/) | シェイプの調整値のコレクションを返します。<br/>            読み取り専用 [`IAdjustValueCollection`](/slides/python-net/ja/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ja/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/ja/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/ja/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/ja/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ja/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/ja/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/ja/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ja/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/ja/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/ja/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/ja/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/ja/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/ja/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/ja/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ja/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/ja/aspose.slides/igeometryshape/get_geometry_paths/#) | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準とした相対座標です。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ja/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) オブジェクトからシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とした相対座標である必要があります。<br/>             シェイプのタイプ ([`IGeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/igeometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ja/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) の配列からシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とした相対座標である必要があります。<br/>             シェイプのタイプ ([`IGeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/igeometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`create_shape_elements(self)`](/slides/python-net/ja/aspose.slides/igeometryshape/create_shape_elements/#) | シェイプの要素の配列を作成して返します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)