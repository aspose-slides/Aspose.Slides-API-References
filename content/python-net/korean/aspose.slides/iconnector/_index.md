---
title: IConnector class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/iconnector/
---
## IConnector 클래스

커넥터를 나타냅니다.

IConnector 유형은 다음 구성원을 표시합니다:

## 속성

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/iconnector/shape_lock/) | 형태의 잠금을 반환합니다.<br/>            읽기 전용 [`IConnectorLock`](/slides/python-net/ko/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/ko/aspose.slides/iconnector/connector_lock/) | Connector의 잠금을 반환합니다.<br/>            읽기 전용 [`IConnectorLock`](/slides/python-net/ko/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/ko/aspose.slides/iconnector/start_shape_connected_to/) | 연결기의 시작을 연결할 형태를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/ko/aspose.slides/iconnector/end_shape_connected_to/) | 연결기의 끝을 연결할 형태를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/ko/aspose.slides/iconnector/start_shape_connection_site_index/) | 시작 형태의 연결 지점 인덱스를 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/ko/aspose.slides/iconnector/end_shape_connection_site_index/) | 끝 형태의 연결 지점 인덱스를 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`shape_style`](/slides/python-net/ko/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/ko/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/ko/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ko/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/ko/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/ko/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/ko/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ko/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/ko/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/ko/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ko/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/ko/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/ko/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/ko/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/ko/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/ko/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/ko/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ko/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/iconnector/hyperlink_manager/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/ko/aspose.slides/iconnector/reroute/#) | 연결기가 연결하는 형태들 사이에서 가능한 가장 짧은 경로를 취하도록 재배치합니다. |
| [`get_geometry_paths(self)`](/slides/python-net/ko/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ko/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ko/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/ko/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/iconnector/get_base_placeholder/#) |  |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)