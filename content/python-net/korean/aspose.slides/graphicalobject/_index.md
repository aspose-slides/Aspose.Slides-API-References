---
title: GraphicalObject class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/graphicalobject/
---
## GraphicalObject 클래스

추상 그래픽 개체를 나타냅니다.

**Inheritance:**[`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

The GraphicalObject type exposes the following members:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/graphicalobject/is_text_holder/) | 도형이 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/graphicalobject/placeholder/) | 도형에 대한 자리표시자를 반환합니다. 도형에 자리표시자가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/graphicalobject/custom_data/) | 도형의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/graphicalobject/raw_frame/) | 원시 도형 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/graphicalobject/frame/) | 도형 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/graphicalobject/line_format/) | 도형의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 유형의 도형은 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/graphicalobject/three_d_format/) | 도형의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 유형의 도형은 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/graphicalobject/effect_format/) | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 유형의 도형은 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/graphicalobject/fill_format/) | 도형의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 유형의 도형은 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/graphicalobject/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/graphicalobject/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/graphicalobject/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides/graphicalobject/hidden/) | 도형이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/graphicalobject/z_order_position/) | z-순서에서 도형의 위치를 반환합니다.<br/>            Shapes[0]은 z-순서의 뒤쪽에 있는 도형을 반환하고,<br/>            Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/graphicalobject/connection_site_count/) | 도형의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/graphicalobject/rotation/) | 지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/graphicalobject/x/) | 도형 왼쪽 위 모서리의 x좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/graphicalobject/y/) | 도형 왼쪽 위 모서리의 y좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/graphicalobject/width/) | 도형의 너비를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/graphicalobject/height/) | 도형의 높이를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/graphicalobject/black_white_mode/) | 속성은 도형이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/graphicalobject/unique_id/) | 애드인이나 기타 코드에서 사용하도록 설계된 프레젠테이션 범위 내부 식별자를 반환합니다.<br/>            이 값은 사용자나 프로그램에 의해 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id)을 참조하십시오. |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/graphicalobject/office_interop_shape_id/) | 도형의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며,<br/>            PowerPoint 또는 인터옵 코드가 문서 어디에서든 도형을 신뢰성 있게 참조할 수 있도록 합니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id)을 참조하십시오. |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/graphicalobject/alternative_text/) | 도형과 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/graphicalobject/alternative_text_title/) | 도형과 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/graphicalobject/name/) | 도형의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요한 경우 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/graphicalobject/is_decorative/) | 'Mark as decorative' 옵션을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/graphicalobject/shape_lock/) | 도형의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/graphicalobject/is_grouped/) | 도형이 그룹화되었는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides/graphicalobject/parent_group/) | 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/graphicalobject/slide/) | 도형의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/graphicalobject/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ko/aspose.slides/graphicalobject/graphical_object_lock/) | 도형의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/graphicalobject/get_image/#) | 도형 썸네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | 도형 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | 도형의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 도형의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/graphicalobject/remove_placeholder/#) | 이 도형이 자리표시자가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | 자리표시자가 없을 경우 새 자리표시자를 추가하고 지정된 자리표시자 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/graphicalobject/get_base_placeholder/#) | 기본 자리표시자 도형을 반환합니다(현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드에서 오는 도형).<br/>            현재 도형이 상속되지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides/graphicalobject/get_visual_bounds/#) | 렌더링된 내용으로 계산된 도형의 시각적 경계를 가져옵니다. |

### 참고
* 클래스 [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)