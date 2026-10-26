---
title: IZoomObject class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/izoomobject/
---
## IZoomObject 클래스

슬라이드에서 Zoom 개체를 나타냅니다.

IZoomObject 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`image_type`](/slides/python-net/ko/aspose.slides/izoomobject/image_type/) | Zoom 개체의 이미지 유형을 가져오거나 설정합니다.<br/>            읽기/쓰기 [`ZoomImageType`](/slides/python-net/ko/aspose.slides/zoomimagetype).<br/>            기본값: Preview |
| [`return_to_parent`](/slides/python-net/ko/aspose.slides/izoomobject/return_to_parent/) | 슬라이드쇼에서 탐색 동작을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**.<br/>            기본값: false |
| [`show_background`](/slides/python-net/ko/aspose.slides/izoomobject/show_background/) | Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**.<br/>            기본값: true |
| [`zoom_image`](/slides/python-net/ko/aspose.slides/izoomobject/zoom_image/) | Zoom 개체의 이미지를 가져오거나 설정합니다.<br/>            읽기/쓰기 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ko/aspose.slides/izoomobject/transition_duration/) | Zoom과 슬라이드 사이 전환의 지속 시간을 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**.<br/>            기본값: 1.0f |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/izoomobject/shape_lock/) |  |
| [`graphical_object_lock`](/slides/python-net/ko/aspose.slides/izoomobject/graphical_object_lock/) |  |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/izoomobject/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ko/aspose.slides/izoomobject/placeholder/) |  |
| [`custom_data`](/slides/python-net/ko/aspose.slides/izoomobject/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/izoomobject/raw_frame/) |  |
| [`frame`](/slides/python-net/ko/aspose.slides/izoomobject/frame/) |  |
| [`line_format`](/slides/python-net/ko/aspose.slides/izoomobject/line_format/) |  |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/izoomobject/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ko/aspose.slides/izoomobject/effect_format/) |  |
| [`fill_format`](/slides/python-net/ko/aspose.slides/izoomobject/fill_format/) |  |
| [`hidden`](/slides/python-net/ko/aspose.slides/izoomobject/hidden/) |  |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/izoomobject/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/izoomobject/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ko/aspose.slides/izoomobject/rotation/) |  |
| [`x`](/slides/python-net/ko/aspose.slides/izoomobject/x/) |  |
| [`y`](/slides/python-net/ko/aspose.slides/izoomobject/y/) |  |
| [`width`](/slides/python-net/ko/aspose.slides/izoomobject/width/) |  |
| [`height`](/slides/python-net/ko/aspose.slides/izoomobject/height/) |  |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/izoomobject/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/izoomobject/alternative_text_title/) |  |
| [`name`](/slides/python-net/ko/aspose.slides/izoomobject/name/) |  |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/izoomobject/is_decorative/) |  |
| [`unique_id`](/slides/python-net/ko/aspose.slides/izoomobject/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/izoomobject/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/izoomobject/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/izoomobject/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ko/aspose.slides/izoomobject/parent_group/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides/izoomobject/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/izoomobject/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/izoomobject/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/izoomobject/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/izoomobject/hyperlink_manager/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/izoomobject/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/izoomobject/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/izoomobject/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/izoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/izoomobject/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/izoomobject/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/izoomobject/get_base_placeholder/#) |  |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)