---
title: IConnector class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iconnector/
---


## IConnector class

Represents a connector.

The IConnector type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/aspose.slides/iconnector/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IConnectorLock`](/slides/python-net/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/aspose.slides/iconnector/connector_lock/) | Returns Connector's locks.<br/>            Read-only [`IConnectorLock`](/slides/python-net/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/aspose.slides/iconnector/start_shape_connected_to/) | Returns or sets the shape to attach the beginning of the connector to.<br/>            Read/write [`IShape`](/slides/python-net/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/aspose.slides/iconnector/end_shape_connected_to/) | Returns or sets the shape to attach the end of the connector to.<br/>            Read/write [`IShape`](/slides/python-net/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/aspose.slides/iconnector/start_shape_connection_site_index/) | Returns or sets the index of connection site for start shape.<br/>            Read/write **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/aspose.slides/iconnector/end_shape_connection_site_index/) | Returns or sets the index of connection site for end shape.<br/>            Read/write **int**. |
| [`shape_style`](/slides/python-net/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/aspose.slides/iconnector/hyperlink_manager/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`get_thumbnail`](/slides/python-net/aspose.slides/iconnector/get_thumbnail/#) |  |
| [`get_thumbnail`](/slides/python-net/aspose.slides/iconnector/get_thumbnail/#shapethumbnailbounds-float-float) |  |
| [`get_image`](/slides/python-net/aspose.slides/iconnector/get_image/#) |  |
| [`get_image`](/slides/python-net/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg`](/slides/python-net/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg`](/slides/python-net/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute`](/slides/python-net/aspose.slides/iconnector/reroute/#) | Reroutes connector so that it take the shortest possible path between the shapes it connect. |
| [`get_geometry_paths`](/slides/python-net/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path`](/slides/python-net/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths`](/slides/python-net/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements`](/slides/python-net/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder`](/slides/python-net/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder`](/slides/python-net/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder`](/slides/python-net/aspose.slides/iconnector/get_base_placeholder/#) |  |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

