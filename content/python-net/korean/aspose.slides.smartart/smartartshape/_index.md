---
title: SmartArtShape class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.smartart/smartartshape/
---
## SmartArtShape 클래스

SmartArt 형식을 나타냅니다.

**상속:**[`SmartArtShape`](/slides/python-net/ko/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

The SmartArtShape type exposes the following members:

## 속성

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/is_text_holder/) | 형식이 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/placeholder/) | 형식에 대한 플레이스홀더를 반환합니다. 형식에 플레이스홀더가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/custom_data/) | 형식의 사용자 지정 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/raw_frame/) | 원시 형식 프레임 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/frame/) | 형식 프레임 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/line_format/) | 형식에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 유형의 형식에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/three_d_format/) | 형식에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 유형의 형식에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/effect_format/) | 형식에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 유형의 형식에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/fill_format/) | 형식에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 유형의 형식에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/hidden/) | 형식이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/z_order_position/) | z-순서에서 형식의 위치를 반환합니다.<br/>            Shapes[0]은 z-순서의 뒤쪽에 있는 형식을 반환하고,<br/>            Shapes[Shapes.Count - 1]은 z-순서의 앞쪽에 있는 형식을 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/connection_site_count/) | 형식의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/rotation/) | 지정된 형식이 z축을 중심으로 회전한 각도를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/x/) | 형식의 왼쪽 위 모서리의 x 좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/y/) | 형식의 왼쪽 위 모서리의 y 좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/width/) | 형식의 너비를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/height/) | 형식의 높이를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/black_white_mode/) | 속성은 형식이 흑백 디스플레이 모드에서 어떻게 렌더링되는지를 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/unique_id/) | 애드인이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다.<br/>            이 값은 사용자나 프로그램에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | 형식의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, PowerPoint 또는 인터옵 코드가 문서 어디서든 형식을 안정적으로 참조할 수 있게 합니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/alternative_text/) | 형식과 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/alternative_text_title/) | 형식과 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/name/) | 형식의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요 시 빈 문자열 값을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/is_decorative/) | '장식으로 표시' 옵션을 얻거나 설정합니다<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/shape_lock/) | 형식의 잠금을 반환합니다.<br/>            읽기 전용 [`IBaseShapeLock`](/slides/python-net/ko/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/is_grouped/) | 형식이 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/parent_group/) | 형식이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/slide/) | 형식의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/shape_style/) | 형식의 스타일 객체를 반환합니다.<br/>            읽기 전용 [`IShapeStyle`](/slides/python-net/ko/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/shape_type/) | 기하학 프리셋 유형을 반환하거나 설정합니다.<br/>            참고: 값을 변경하면 모든 조정 값이 기본값으로 재설정됩니다.<br/>            읽기/쓰기 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/adjustments/) | 형식의 조정 값 컬렉션을 반환합니다.<br/>            읽기 전용 [`IAdjustValueCollection`](/slides/python-net/ko/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/text_frame/) | SmartArt 형식의 텍스트를 반환합니다.<br/>            읽기 전용 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe). |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/get_image/#) | 형식 썸네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape 형식의 썸네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | 형식 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | 형식의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 형식의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/remove_placeholder/#) | 이 형식이 플레이스홀더가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더에 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | 기본 플레이스홀더 형식을 반환합니다(현재 형식이 상속받은 레이아웃 및/또는 마스터 슬라이드의 형식).<br/>            현재 형식이 상속받지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | 렌더링된 내용으로부터 계산된 형식의 시각적 경계를 가져옵니다. |
| [`get_geometry_paths(self)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | 기하학 형식 경로의 복사본을 반환합니다. 좌표는 형식의 왼쪽 위 모서리를 기준으로 합니다. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 객체에서 형식 기하학을 업데이트합니다. 좌표는 형식의 왼쪽 위 모서리를 기준으로 해야 합니다.<br/>            형식의 유형 ([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)으로 변경합니다. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 배열에서 형식 기하학을 업데이트합니다. 좌표는 형식의 왼쪽 위 모서리를 기준으로 해야 합니다.<br/>            형식의 유형 ([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)으로 변경합니다. |
| [`create_shape_elements(self)`](/slides/python-net/ko/aspose.slides.smartart/smartartshape/create_shape_elements/#) | 형식 요소 배열을 만들고 반환합니다. |

### 참고
* 클래스 [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 클래스 [`SmartArtShape`](/slides/python-net/ko/aspose.slides.smartart/smartartshape)
* 모듈 [`aspose.slides.smartart`](/slides/python-net/ko/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)