---
title: IConnector class
second_title: Aspose.Slides for Python via .NET の API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iconnector/
---
## IConnector クラス

コネクタを表します。

IConnector 型は次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/iconnector/shape_lock/) | Returns shape's locks.<br/>            読み取り専用 [`IConnectorLock`](/slides/python-net/ja/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/ja/aspose.slides/iconnector/connector_lock/) | Returns Connector's locks.<br/>            読み取り専用 [`IConnectorLock`](/slides/python-net/ja/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/ja/aspose.slides/iconnector/start_shape_connected_to/) | Returns or sets the shape to attach the beginning of the connector to.<br/>            読み書き可能 [`IShape`](/slides/python-net/ja/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/ja/aspose.slides/iconnector/end_shape_connected_to/) | Returns or sets the shape to attach the end of the connector to.<br/>            読み書き可能 [`IShape`](/slides/python-net/ja/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/ja/aspose.slides/iconnector/start_shape_connection_site_index/) | Returns or sets the index of connection site for start shape.<br/>            読み書き可能 **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/ja/aspose.slides/iconnector/end_shape_connection_site_index/) | Returns or sets the index of connection site for end shape.<br/>            読み書き可能 **int**. |
| [`shape_style`](/slides/python-net/ja/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/ja/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/ja/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ja/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/ja/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/ja/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/ja/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ja/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/ja/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/ja/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ja/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/ja/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/ja/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/ja/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/ja/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/ja/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/ja/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ja/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/iconnector/hyperlink_manager/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/ja/aspose.slides/iconnector/reroute/#) | コネクタのルートを再設定し、接続するシェイプ間の最短パスを取るようにします。 |
| [`get_geometry_paths(self)`](/slides/python-net/ja/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ja/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ja/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/ja/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/iconnector/get_base_placeholder/#) |  |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)