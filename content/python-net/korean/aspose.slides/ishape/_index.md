---
title: IShape class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ishape/
---
## IShape 클래스

슬라이드의 도형을 나타냅니다.

IShape 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/ishape/is_text_holder/) | 도형이 TextHolder인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/ishape/placeholder/) | 도형에 대한 자리 표시자를 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/ishape/custom_data/) | 도형의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/ishape/raw_frame/) | 원시 도형 프레임 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/ishape/frame/) | 도형 프레임 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/ishape/line_format/) | 도형의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/ishape/three_d_format/) | 도형의 3D 서식 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/ishape/effect_format/) | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/ishape/fill_format/) | 도형의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/ko/aspose.slides/ishape/hidden/) | 도형이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/ishape/z_order_position/) | z-순서에서 도형의 위치를 반환합니다.<br/>            Shapes[0]은 z-순서의 뒤쪽에 있는 도형을 반환하고,<br/>            Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/ishape/connection_site_count/) | 도형의 연결 지점 개수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/ishape/rotation/) | 지정된 도형이 z축을 중심으로 회전한 각도를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/ishape/x/) | 도형 좌상단 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/ishape/y/) | 도형 좌상단 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/ishape/width/) | 도형의 너비를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/ishape/height/) | 도형의 높이를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/ishape/alternative_text/) | 도형에 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/ishape/alternative_text_title/) | 도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/ishape/name/) | 도형의 이름을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/ishape/is_decorative/) | 'Mark as decorative' 옵션을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/ishape/shape_lock/) | 도형의 잠금을 반환합니다.<br/>            읽기 전용 [`IBaseShapeLock`](/slides/python-net/ko/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/ishape/unique_id/) | 애드인이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다.<br/>            이 값은 사용자나 프로그램에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`IShape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/ishape/office_interop_shape_id)를 참조하십시오. |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/ishape/office_interop_shape_id/) | 도형의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며,<br/>            PowerPoint 또는 인터옵 코드가 문서 어디에서든 도형을 신뢰성 있게 참조할 수 있도록 합니다.<br/>            읽기 전용 **int**.<br/>            또한 [`IShape.unique_id`](/slides/python-net/ko/aspose.slides/ishape/unique_id)를 참조하십시오. |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/ishape/is_grouped/) | 도형이 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/ishape/black_white_mode/) | 이 속성은 흑백 표시 모드에서 도형이 어떻게 렌더링되는지를 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/ko/aspose.slides/ishape/parent_group/) | 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/ishape/hyperlink_manager/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/ishape/get_image/#) | 도형 썸네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | 도형 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/ishape/write_as_svg/#iorawiobase) | 도형의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 도형의 내용을 SVG 파일로 저장합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/ishape/add_placeholder/#iplaceholder) | 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더 속성을 설정합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/ishape/remove_placeholder/#) | 이 도형이 플레이스홀더가 아님을 정의합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/ishape/get_base_placeholder/#) | 기본 플레이스홀더 도형을 반환합니다(현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 도형).<br/>            현재 도형이 상속받지 않은 경우 None을 반환합니다. |

### 관련 항목
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)