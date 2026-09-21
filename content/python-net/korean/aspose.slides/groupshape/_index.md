---
title: GroupShape class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/groupshape/
---
## GroupShape 클래스

Represents a group of shapes on a slide.

**Inheritance:**[`GroupShape`](/slides/python-net/ko/aspose.slides/groupshape) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

The GroupShape type exposes the following members:

## 속성

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/groupshape/is_text_holder/) | 형태가 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/groupshape/placeholder/) | 형태에 대한 placeholder를 반환합니다. 형태에 placeholder가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/groupshape/custom_data/) | 형태의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/groupshape/raw_frame/) | 원시 형태 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/groupshape/frame/) | 형태 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/groupshape/line_format/) | 형태에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: GroupShape 객체는 선 속성이 없으므로 None을 반환합니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/groupshape/three_d_format/) | 형태에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 형태 유형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/groupshape/effect_format/) | 형태에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 형태 유형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/groupshape/fill_format/) | 형태에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 형태 유형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/groupshape/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/groupshape/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/groupshape/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides/groupshape/hidden/) | 형태가 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/groupshape/z_order_position/) | z-순서에서 형태의 위치를 반환합니다.<br/>            Shapes[0]은 z-순서의 뒤쪽에 있는 형태를 반환하고,<br/>            Shapes[Shapes.Count - 1]은 z-순서의 앞쪽에 있는 형태를 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/groupshape/connection_site_count/) | 형태의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/groupshape/rotation/) | 지정된 형태가 z축을 중심으로 회전한 각도(도) 수를 반환하거나 설정합니다.<br/>            양의 값은 시계 방향 회전을 나타내고, 음의 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/groupshape/x/) | 형태의 좌상단 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/groupshape/y/) | 형태의 좌상단 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/groupshape/width/) | 형태의 너비를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/groupshape/height/) | 형태의 높이를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/groupshape/black_white_mode/) | 속성은 형태가 흑백 디스플레이 모드에서 어떻게 렌더링되는지를 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/groupshape/unique_id/) | 애드인이나 기타 코드에서 사용하도록 의도된 내부 프레젠테이션 범위 식별자를 반환합니다.<br/>            이 값은 사용자나 프로그램에 의해 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id)를 참조하십시오. |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/groupshape/office_interop_shape_id/) | 형태의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며,<br/>            이를 통해 PowerPoint 또는 인터옵 코드가 문서 어디에서든 형태를 안정적으로 참조할 수 있습니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id)를 참조하십시오. |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/groupshape/alternative_text/) | 형태와 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/groupshape/alternative_text_title/) | 형태와 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/groupshape/name/) | 형태의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요시 빈 문자열 값을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/groupshape/is_decorative/) | ‘Mark as decorative’ 옵션을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/groupshape/shape_lock/) | 형태의 잠금을 반환합니다.<br/>            읽기 전용 [`IGroupShapeLock`](/slides/python-net/ko/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/groupshape/is_grouped/) | 형태가 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides/groupshape/parent_group/) | 형태가 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/groupshape/slide/) | 형태의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/groupshape/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/ko/aspose.slides/groupshape/group_shape_lock/) | 형태의 잠금을 반환합니다.<br/>            읽기 전용 [`IGroupShapeLock`](/slides/python-net/ko/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/ko/aspose.slides/groupshape/shapes/) | 그룹 내부의 형태 컬렉션을 반환합니다.<br/>            읽기 전용 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection). |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/groupshape/get_image/#) | 형태 섬네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape 형태 섬네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | 형태 섬네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/groupshape/remove_placeholder/#) | 이 형태가 placeholder가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/groupshape/add_placeholder/#iplaceholder) | placeholder가 없을 경우 새로운 placeholder를 추가하고 지정된 placeholder의 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/groupshape/get_base_placeholder/#) | 기본 placeholder 형태를 반환합니다(현재 형태가 상속받은 레이아웃 및/또는 마스터 슬라이드의 형태).<br/>            현재 형태가 상속받지 않으면 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides/groupshape/get_visual_bounds/#) | 렌더링된 내용으로 계산된 형태의 시각적 경계를 가져옵니다. |

### 참고
* 클래스 [`GroupShape`](/slides/python-net/ko/aspose.slides/groupshape)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)