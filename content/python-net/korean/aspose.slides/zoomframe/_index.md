---
title: ZoomFrame class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/zoomframe/
---
## ZoomFrame 클래스

슬라이드에 있는 Slide Zoom 객체를 나타냅니다.

**Inheritance:**[`ZoomFrame`](/slides/python-net/ko/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/ko/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

ZoomFrame 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/zoomframe/is_text_holder/) | 형상이 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/zoomframe/placeholder/) | 형상의 자리 표시자를 반환합니다. 형상에 자리 표시자가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/zoomframe/custom_data/) | 형상의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/zoomframe/raw_frame/) | 원시 형상 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/zoomframe/frame/) | 형상 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/zoomframe/line_format/) | 형상의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 유형의 형상에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/zoomframe/three_d_format/) | 형상의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 유형의 형상에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/zoomframe/effect_format/) | 형상에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 유형의 형상에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/zoomframe/fill_format/) | 형상의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 유형의 형상에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/zoomframe/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/zoomframe/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/zoomframe/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides/zoomframe/hidden/) | 형상이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/zoomframe/z_order_position/) | 형상의 Z-순서에서 위치를 반환합니다.<br/>            Shapes[0]은 Z-순서의 뒤쪽에 있는 형상을 반환하고,<br/>            Shapes[Shapes.Count - 1]은 앞쪽에 있는 형상을 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/zoomframe/connection_site_count/) | 형상의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/zoomframe/rotation/) | 지정된 형상이 Z축을 중심으로 회전된 각도를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을 나타내며, 음수 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/zoomframe/x/) | 형상의 왼쪽 위 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/zoomframe/y/) | 형상의 왼쪽 위 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/zoomframe/width/) | 형상의 너비를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/zoomframe/height/) | 형상의 높이를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/zoomframe/black_white_mode/) | 속성은 형상이 흑백 디스플레이 모드에서 어떻게 렌더링되는지를 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/zoomframe/unique_id/) | 애드인 또는 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다.<br/>            이 값은 사용자에 의해 또는 프로그래밍 방식으로 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또 보기 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/zoomframe/office_interop_shape_id/) | 형상의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하고,<br/>            PowerPoint 또는 인터옵 코드가 문서 어디서든 형상을 안정적으로 참조할 수 있게 합니다.<br/>            읽기 전용 **int**.<br/>            또 보기 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/zoomframe/alternative_text/) | 형상에 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/zoomframe/alternative_text_title/) | 형상에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/zoomframe/name/) | 형상의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/zoomframe/is_decorative/) | '장식으로 표시' 옵션을 가져오거나 설정합니다<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/zoomframe/shape_lock/) | 형상의 잠금을 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/zoomframe/is_grouped/) | 형상이 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides/zoomframe/parent_group/) | 형상이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/zoomframe/slide/) | 형상의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/zoomframe/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ko/aspose.slides/zoomframe/graphical_object_lock/) | 형상의 잠금을 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/ko/aspose.slides/zoomframe/image_type/) | 줌 객체의 이미지 유형을 가져오거나 설정합니다.<br/>            읽기/쓰기 [`ZoomImageType`](/slides/python-net/ko/aspose.slides/zoomimagetype).<br/>            기본값: Preview |
| [`return_to_parent`](/slides/python-net/ko/aspose.slides/zoomframe/return_to_parent/) | 슬라이드 쇼에서 네비게이션 동작을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**.<br/>            기본값: false |
| [`show_background`](/slides/python-net/ko/aspose.slides/zoomframe/show_background/) | Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**.<br/>            기본값: true |
| [`zoom_image`](/slides/python-net/ko/aspose.slides/zoomframe/zoom_image/) | 줌 객체의 이미지를 가져오거나 설정합니다.<br/>            읽기/쓰기 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ko/aspose.slides/zoomframe/transition_duration/) | Zoom과 슬라이드 간 전환 지속 시간을 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**.<br/>            기본값: 1.0f |
| [`target_slide`](/slides/python-net/ko/aspose.slides/zoomframe/target_slide/) | Slide Zoom 객체가 연결되는 슬라이드 객체를 가져오거나 설정합니다.<br/>            읽기/쓰기 [`ISlide`](/slides/python-net/ko/aspose.slides/islide). |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/zoomframe/get_image/#) | 형상 썸네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape 형상 썸네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | 형상 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | 형상의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 형상의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/zoomframe/remove_placeholder/#) | 이 형상이 자리 표시자가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | 자리 표시자가 없으면 새 자리 표시자를 추가하고 지정된 자리 표시자 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/zoomframe/get_base_placeholder/#) | 기본 자리 표시자 형상을 반환합니다(현재 형상이 상속받은 레이아웃 및/또는 마스터 슬라이드의 형상).<br/>            현재 형상이 상속되지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides/zoomframe/get_visual_bounds/#) | 렌더링된 내용으로부터 계산된 형상의 시각적 경계를 가져옵니다. |

### 참고
* 클래스 [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 클래스 [`ZoomFrame`](/slides/python-net/ko/aspose.slides/zoomframe)
* 클래스 [`ZoomObject`](/slides/python-net/ko/aspose.slides/zoomobject)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)