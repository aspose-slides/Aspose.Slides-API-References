---
title: IGeometryShape class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/igeometryshape/
---
## IGeometryShape 클래스

모든 기하학적 도형의 부모 클래스를 나타냅니다.

IGeometryShape 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/ko/aspose.slides/igeometryshape/shape_style/) | 도형의 스타일 개체를 반환합니다.<br/>            읽기 전용 [`IShapeStyle`](/slides/python-net/ko/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ko/aspose.slides/igeometryshape/shape_type/) | 기하학 사전 설정 유형을 반환하거나 설정합니다.<br/>            참고: 값을 변경하면 모든 조정 값이 기본값으로 재설정됩니다.<br/>            읽기/쓰기 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ko/aspose.slides/igeometryshape/adjustments/) | 도형의 조정 값 컬렉션을 반환합니다.<br/>            읽기 전용 [`IAdjustValueCollection`](/slides/python-net/ko/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ko/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/ko/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/ko/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/ko/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ko/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/ko/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/ko/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ko/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/ko/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/ko/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/ko/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/ko/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/ko/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/ko/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ko/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/ko/aspose.slides/igeometryshape/get_geometry_paths/#) | 기하학 도형 경로의 복사본을 반환합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 합니다. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ko/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 객체에서 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽<br/>             상단 모서리를 기준이어야 합니다.<br/>             도형 유형을 ([`IGeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/igeometryshape/shape_type))에서 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM) 로 변경합니다. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ko/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 배열에서 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽<br/>             상단 모서리를 기준이어야 합니다.<br/>             도형 유형을 ([`IGeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/igeometryshape/shape_type))에서 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM) 로 변경합니다. |
| [`create_shape_elements(self)`](/slides/python-net/ko/aspose.slides/igeometryshape/create_shape_elements/#) | 도형 요소의 배열을 생성하고 반환합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)