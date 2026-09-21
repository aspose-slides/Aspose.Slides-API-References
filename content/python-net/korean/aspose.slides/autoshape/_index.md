---
title: AutoShape class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/autoshape/
---
## AutoShape 클래스

AutoShape을 나타냅니다.

**상속:**[`AutoShape`](/slides/python-net/ko/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

AutoShape 타입은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/autoshape/is_text_holder/) | shape가 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/autoshape/placeholder/) | shape의 자리표시자를 반환합니다. shape에 자리표시자가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/autoshape/custom_data/) | shape의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/autoshape/raw_frame/) | 원시 shape 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/autoshape/frame/) | shape 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/autoshape/line_format/) | shape의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 shape 유형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/autoshape/three_d_format/) | shape의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 shape 유형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/autoshape/effect_format/) | shape에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 shape 유형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/autoshape/fill_format/) | shape의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 shape 유형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/autoshape/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/autoshape/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/autoshape/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides/autoshape/hidden/) | shape가 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/autoshape/z_order_position/) | shape가 z-순서에서 차지하는 위치를 반환합니다.<br/>            Shapes[0]은 z-순서 뒤쪽에 있는 shape를 반환하고,<br/>            Shapes[Shapes.Count - 1]은 앞쪽에 있는 shape를 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/autoshape/connection_site_count/) | shape의 연결 지점 개수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/autoshape/rotation/) | 지정된 shape가 z축을 중심으로 회전한 각도를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/autoshape/x/) | shape의 왼쪽 위 모서리의 x좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/autoshape/y/) | shape의 왼쪽 위 모서리의 y좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/autoshape/width/) | shape의 너비를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/autoshape/height/) | shape의 높이를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/autoshape/black_white_mode/) | shape가 흑백 표시 모드에서 어떻게 렌더링될지를 지정하는 속성입니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/autoshape/unique_id/) | 애드인이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다.<br/>            이 값은 사용자 또는 프로그램에 의해 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id)을(를) 참조하십시오. |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/autoshape/office_interop_shape_id/) | shape의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며,<br/>            PowerPoint 또는 인터옵 코드를 통해 문서의 어느 위치에서든 shape를 안정적으로 참조할 수 있게 합니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id)을(를) 참조하십시오. |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/autoshape/alternative_text/) | shape와 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/autoshape/alternative_text_title/) | shape와 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/autoshape/name/) | shape의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/autoshape/is_decorative/) | '장식으로 표시' 옵션을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/autoshape/shape_lock/) | shape의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IAutoShapeLock`](/slides/python-net/ko/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/autoshape/is_grouped/) | shape가 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides/autoshape/parent_group/) | shape가 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/autoshape/slide/) | shape의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/autoshape/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ko/aspose.slides/autoshape/shape_style/) | shape의 스타일 객체를 반환합니다.<br/>            읽기 전용 [`IShapeStyle`](/slides/python-net/ko/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ko/aspose.slides/autoshape/shape_type/) | 기하학 사전 설정 유형을 반환하거나 설정합니다.<br/>            참고: 값이 변경되면 모든 조정 값이 기본값으로 재설정됩니다.<br/>            읽기/쓰기 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ko/aspose.slides/autoshape/adjustments/) | shape의 조정 값 컬렉션을 반환합니다.<br/>            읽기 전용 [`IAdjustValueCollection`](/slides/python-net/ko/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/ko/aspose.slides/autoshape/auto_shape_lock/) | autoshape의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IAutoShapeLock`](/slides/python-net/ko/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/ko/aspose.slides/autoshape/text_frame/) | AutoShape에 대한 TextFrame 객체를 반환합니다.<br/>            읽기 전용 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/ko/aspose.slides/autoshape/use_background_fill/) | 이 autoshape가 스타일이나 채우기 형식으로 지정된 것이 아니라 슬라이드 배경 채우기로 채워져야 하는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`is_text_box`](/slides/python-net/ko/aspose.slides/autoshape/is_text_box/) | shape가 텍스트 상자인지 여부를 지정합니다. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/autoshape/get_image/#) | shape 썸네일을 반환합니다.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | shape 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/autoshape/remove_placeholder/#) | 이 shape가 자리표시자가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/autoshape/add_placeholder/#iplaceholder) | 자리표시자가 없을 경우 새 자리표시자를 추가하고 지정된 자리표시자 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/autoshape/get_base_placeholder/#) | 기본 자리표시자 shape를 반환합니다(현재 shape가 상속받은 레이아웃 및/또는 마스터 슬라이드의 shape).<br/>            현재 shape가 상속받지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides/autoshape/get_visual_bounds/#) | 렌더링된 내용으로부터 계산된 shape의 시각적 경계를 가져옵니다. |
| [`get_geometry_paths(self)`](/slides/python-net/ko/aspose.slides/autoshape/get_geometry_paths/#) | 기하학 shape의 경로 복사본을 반환합니다. 좌표는 shape의 왼쪽 상단 모서리를 기준으로 합니다. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ko/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 객체를 사용하여 shape의 기하학을 업데이트합니다. 좌표는 shape의 왼쪽<br/>             상단 모서리를 기준으로 해야 합니다.<br/>             shape의 유형([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)(으)로 변경합니다. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ko/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 배열을 사용하여 shape의 기하학을 업데이트합니다. 좌표는 shape의 왼쪽<br/>             상단 모서리를 기준으로 해야 합니다.<br/>             shape의 유형([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)(으)로 변경합니다. |
| [`create_shape_elements(self)`](/slides/python-net/ko/aspose.slides/autoshape/create_shape_elements/#) | shape 요소들의 배열을 생성하고 반환합니다. |
| [`add_text_frame(self, text)`](/slides/python-net/ko/aspose.slides/autoshape/add_text_frame/#str) | shape에 새 TextFrame을 추가합니다.<br/>            shape가 이미 TextFrame을 가지고 있으면 단순히 텍스트를 변경합니다. |

### 관련 항목
* 클래스 [`AutoShape`](/slides/python-net/ko/aspose.slides/autoshape)
* 클래스 [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)