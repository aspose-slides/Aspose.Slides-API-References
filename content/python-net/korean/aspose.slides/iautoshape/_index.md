---
title: IAutoShape class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/iautoshape/
---
## IAutoShape 클래스

AutoShape을 나타냅니다.

IAutoShape 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/iautoshape/shape_lock/) | 형상의 잠금을 반환합니다.<br/>읽기 전용 [`IAutoShapeLock`](/slides/python-net/ko/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/ko/aspose.slides/iautoshape/auto_shape_lock/) | AutoShape의 잠금을 반환합니다.<br/>읽기 전용 [`IAutoShapeLock`](/slides/python-net/ko/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/ko/aspose.slides/iautoshape/text_frame/) | AutoShape에 대한 TextFrame 객체를 반환합니다.<br/>읽기 전용 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/ko/aspose.slides/iautoshape/use_background_fill/) | 이 자동 도형이 스타일이나 채우기 형식이 지정된 대신 슬라이드 배경 채우기로 채워져야 하는지 여부를 결정합니다.<br/>읽기/쓰기 **bool**. |
| [`is_text_box`](/slides/python-net/ko/aspose.slides/iautoshape/is_text_box/) | 도형이 텍스트 상자인지 여부를 지정합니다. |
| [`shape_style`](/slides/python-net/ko/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/ko/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/ko/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ko/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/ko/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/ko/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/ko/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ko/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/ko/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/ko/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ko/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/ko/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/ko/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/ko/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/ko/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/ko/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/ko/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ko/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/iautoshape/hyperlink_manager/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/ko/aspose.slides/iautoshape/add_text_frame/#str) | 새 TextFrame을 도형에 추가합니다.<br/>도형에 이미 TextFrame이 있는 경우 단순히 텍스트를 변경합니다. |
| [`get_geometry_paths(self)`](/slides/python-net/ko/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ko/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ko/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/ko/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/iautoshape/get_base_placeholder/#) |  |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)