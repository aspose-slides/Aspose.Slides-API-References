---
title: SectionZoomFrame class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame 클래스

Represents a Section Zoom object in a slide.

**Inheritance:**[`SectionZoomFrame`](/slides/python-net/ko/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/ko/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

The SectionZoomFrame type exposes the following members:

## 속성

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/sectionzoomframe/is_text_holder/) | shape가 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/sectionzoomframe/placeholder/) | shape에 대한 placeholder를 반환합니다. shape에 placeholder가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/sectionzoomframe/custom_data/) | shape의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/sectionzoomframe/raw_frame/) | 원시 shape 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/sectionzoomframe/frame/) | shape 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/sectionzoomframe/line_format/) | shape의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 유형의 shape에서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/sectionzoomframe/three_d_format/) | shape의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 유형의 shape에서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/sectionzoomframe/effect_format/) | shape에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 유형의 shape에서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/sectionzoomframe/fill_format/) | shape의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 일부 shape에서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/sectionzoomframe/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/sectionzoomframe/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides/sectionzoomframe/hidden/) | shape가 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/sectionzoomframe/z_order_position/) | z-order에서 shape의 위치를 반환합니다.<br/>            Shapes[0]은 z-order의 뒤쪽에 있는 shape를 반환하고,<br/>            Shapes[Shapes.Count - 1]은 앞쪽에 있는 shape를 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/sectionzoomframe/connection_site_count/) | shape의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/sectionzoomframe/rotation/) | 지정된 shape가 z축을 중심으로 회전한 각도를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/sectionzoomframe/x/) | shape의 왼쪽 위 모서리의 x좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/sectionzoomframe/y/) | shape의 왼쪽 위 모서리의 y좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/sectionzoomframe/width/) | shape의 너비를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/sectionzoomframe/height/) | shape의 높이를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/sectionzoomframe/black_white_mode/) | shape가 흑백 표시 모드에서 어떻게 렌더링될지 지정하는 속성입니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/sectionzoomframe/unique_id/) | add-in이나 기타 코드에서 사용하도록 설계된 프레젠테이션 범위 내부 식별자를 반환합니다.<br/>            이 값은 사용자나 프로그래밍으로 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id)을(를) 참조하십시오. |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/sectionzoomframe/office_interop_shape_id/) | shape의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며,<br/>            PowerPoint 또는 인터옵 코드가 문서 어디서든 shape를 신뢰하게 참조할 수 있도록 합니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id)을(를) 참조하십시오. |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/sectionzoomframe/alternative_text/) | shape와 연관된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/sectionzoomframe/alternative_text_title/) | shape와 연관된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/sectionzoomframe/name/) | shape의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/sectionzoomframe/is_decorative/) | '장식용으로 표시' 옵션을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/sectionzoomframe/shape_lock/) | shape의 잠금을 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/sectionzoomframe/is_grouped/) | shape가 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides/sectionzoomframe/parent_group/) | shape가 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/sectionzoomframe/slide/) | shape의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/sectionzoomframe/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ko/aspose.slides/sectionzoomframe/graphical_object_lock/) | shape의 잠금을 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/ko/aspose.slides/sectionzoomframe/image_type/) | zoom 객체의 이미지 유형을 가져오거나 설정합니다.<br/>            읽기/쓰기 [`ZoomImageType`](/slides/python-net/ko/aspose.slides/zoomimagetype).<br/>            기본값: Preview |
| [`return_to_parent`](/slides/python-net/ko/aspose.slides/sectionzoomframe/return_to_parent/) | 슬라이드쇼에서 네비게이션 동작을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**.<br/>            기본값: false |
| [`show_background`](/slides/python-net/ko/aspose.slides/sectionzoomframe/show_background/) | Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**.<br/>            기본값: true |
| [`zoom_image`](/slides/python-net/ko/aspose.slides/sectionzoomframe/zoom_image/) | zoom 객체의 이미지를 가져오거나 설정합니다.<br/>            읽기/쓰기 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ko/aspose.slides/sectionzoomframe/transition_duration/) | Zoom과 슬라이드 사이 전환 지속 시간을 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**.<br/>            기본값: 1.0f |
| [`target_section`](/slides/python-net/ko/aspose.slides/sectionzoomframe/target_section/) | Section Zoom 객체가 연결되는 섹션 객체를 가져오거나 설정합니다.<br/>            읽기/쓰기 [`ISection`](/slides/python-net/ko/aspose.slides/isection). |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/sectionzoomframe/get_image/#) | shape 썸네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape shape 썸네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | shape 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/sectionzoomframe/remove_placeholder/#) | 이 shape가 placeholder가 아니도록 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | placeholder가 없으면 새 placeholder를 추가하고 지정된 placeholder의 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/sectionzoomframe/get_base_placeholder/#) | 기본 placeholder shape를 반환합니다(현재 shape가 상속받은 레이아웃 및/또는 마스터 슬라이드의 shape).<br/>            현재 shape가 상속받지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides/sectionzoomframe/get_visual_bounds/#) | 렌더링된 콘텐츠를 기반으로 계산된 shape의 시각적 경계를 가져옵니다. |

### 참고
* 클래스 [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject)
* 클래스 [`SectionZoomFrame`](/slides/python-net/ko/aspose.slides/sectionzoomframe)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 클래스 [`ZoomObject`](/slides/python-net/ko/aspose.slides/zoomobject)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)