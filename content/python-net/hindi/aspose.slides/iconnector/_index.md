---
title: IConnector class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iconnector/
---
## IConnector क्लास

Represents a connector.

The IConnector type exposes the following members:

## गुण

| गुण | विवरण |
| :- | :- |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/iconnector/shape_lock/) | आकार की लॉक़ को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IConnectorLock`](/slides/python-net/hi/aspose.slides/iconnectorlock)। |
| [`connector_lock`](/slides/python-net/hi/aspose.slides/iconnector/connector_lock/) | Connector की लॉक़ को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IConnectorLock`](/slides/python-net/hi/aspose.slides/iconnectorlock)। |
| [`start_shape_connected_to`](/slides/python-net/hi/aspose.slides/iconnector/start_shape_connected_to/) | कनेक्टर की शुरुआत को संलग्न करने के लिये आकार को प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShape`](/slides/python-net/hi/aspose.slides/ishape)। |
| [`end_shape_connected_to`](/slides/python-net/hi/aspose.slides/iconnector/end_shape_connected_to/) | कनेक्टर के अंत को संलग्न करने के लिये आकार को प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShape`](/slides/python-net/hi/aspose.slides/ishape)। |
| [`start_shape_connection_site_index`](/slides/python-net/hi/aspose.slides/iconnector/start_shape_connection_site_index/) | प्रारंभिक आकार के लिये कनेक्शन साइट का सूचकांक प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`end_shape_connection_site_index`](/slides/python-net/hi/aspose.slides/iconnector/end_shape_connection_site_index/) | अंत आकार के लिये कनेक्शन साइट का सूचकांक प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`shape_style`](/slides/python-net/hi/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/hi/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/hi/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/hi/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/hi/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/hi/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/hi/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/hi/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/hi/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/hi/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/hi/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/hi/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/hi/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/hi/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/hi/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/hi/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/hi/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/hi/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/hi/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/iconnector/hyperlink_manager/) |  |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/hi/aspose.slides/iconnector/reroute/#) | कनेक्टर को पुनः मार्गित करता है ताकि वह उन आकारों के बीच सबसे छोटा संभव पथ ले सके जिनसे यह जुड़ा है। |
| [`get_geometry_paths(self)`](/slides/python-net/hi/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hi/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hi/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/hi/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/iconnector/get_base_placeholder/#) |  |


### देखें अन्य
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* पुस्तकालय [`Aspose.Slides`](/slides/python-net)