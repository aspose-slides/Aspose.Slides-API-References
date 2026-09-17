---
title: IConnector class
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iconnector/
---
## IConnector 类

表示一个连接器。

IConnector 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/zh/aspose.slides/iconnector/shape_lock/) | 返回形状的锁。<br/>            只读 [`IConnectorLock`](/slides/python-net/zh/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/zh/aspose.slides/iconnector/connector_lock/) | 返回连接器的锁。<br/>            只读 [`IConnectorLock`](/slides/python-net/zh/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/zh/aspose.slides/iconnector/start_shape_connected_to/) | 返回或设置用于连接器起始端的形状。<br/>            读/写 [`IShape`](/slides/python-net/zh/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/zh/aspose.slides/iconnector/end_shape_connected_to/) | 返回或设置用于连接器结束端的形状。<br/>            读/写 [`IShape`](/slides/python-net/zh/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/zh/aspose.slides/iconnector/start_shape_connection_site_index/) | 返回或设置起始形状的连接点索引。<br/>            读/写 **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/zh/aspose.slides/iconnector/end_shape_connection_site_index/) | 返回或设置结束形状的连接点索引。<br/>            读/写 **int**. |
| [`shape_style`](/slides/python-net/zh/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/zh/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/zh/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/zh/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/zh/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/zh/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/zh/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/zh/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/zh/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/zh/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/zh/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/zh/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/zh/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/zh/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/zh/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/zh/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/zh/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/zh/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/zh/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/zh/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/zh/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/zh/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/zh/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/iconnector/hyperlink_manager/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/zh/aspose.slides/iconnector/reroute/#) | 重新路由连接器，使其在连接的形状之间采用最短可能路径。 |
| [`get_geometry_paths(self)`](/slides/python-net/zh/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/zh/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides/iconnector/get_base_placeholder/#) |  |


### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)