---
title: SmartArt class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.smartart/smartart/
---
## SmartArt 클래스

SmartArt 다이어그램을 나타냅니다

**상속:**[`SmartArt`](/slides/python-net/ko/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

SmartArt 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides.smartart/smartart/is_text_holder/) | 형상이 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides.smartart/smartart/placeholder/) | 형상의 플레이스홀더를 반환합니다. 형상에 플레이스홀더가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides.smartart/smartart/custom_data/) | 형상의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides.smartart/smartart/raw_frame/) | 원시 형상 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides.smartart/smartart/frame/) | 형상 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides.smartart/smartart/line_format/) | 형상의 선 형식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 유형의 형상에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides.smartart/smartart/three_d_format/) | 형상의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 유형의 형상에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides.smartart/smartart/effect_format/) | 형상에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 유형의 형상에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides.smartart/smartart/fill_format/) | 형상의 채우기 형식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 유형의 형상에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides.smartart/smartart/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides.smartart/smartart/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides.smartart/smartart/hidden/) | 형상이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides.smartart/smartart/z_order_position/) | z-순서에서 형상의 위치를 반환합니다.<br/>            Shapes[0]은 z-순서 맨 뒤에 있는 형상을 반환하고,<br/>            Shapes[Shapes.Count - 1]은 z-순서 맨 앞에 있는 형상을 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides.smartart/smartart/connection_site_count/) | 형상의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides.smartart/smartart/rotation/) | 지정된 형상이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides.smartart/smartart/x/) | 형상의 왼쪽 위 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides.smartart/smartart/y/) | 형상의 왼쪽 위 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides.smartart/smartart/width/) | 형상의 너비를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides.smartart/smartart/height/) | 형상의 높이를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides.smartart/smartart/black_white_mode/) | 속성은 형상이 흑백 표시 모드에서 어떻게 렌더링될지를 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides.smartart/smartart/unique_id/) | 프레젠테이션 범위 내부 식별자를 반환합니다. 이 값은 애드인이나 다른 코드에서 사용하기 위한 것입니다.<br/>            이 값은 사용자 또는 프로그래밍 방식으로 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id)을(를) 참조하십시오. |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides.smartart/smartart/office_interop_shape_id/) | 슬라이드 범위 고유 식별자를 반환합니다. 이 식별자는 형상의 수명 동안 일정하게 유지되어 PowerPoint나 인터옵 코드가 문서 어디서든 형상을 안정적으로 참조할 수 있게 합니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id)을(를) 참조하십시오. |
| [`alternative_text`](/slides/python-net/ko/aspose.slides.smartart/smartart/alternative_text/) | 형상에 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides.smartart/smartart/alternative_text_title/) | 형상에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides.smartart/smartart/name/) | 형상의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides.smartart/smartart/is_decorative/) | ‘장식으로 표시’ 옵션을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides.smartart/smartart/shape_lock/) | 형상의 잠금을 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides.smartart/smartart/is_grouped/) | 형상이 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides.smartart/smartart/parent_group/) | 형상이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides.smartart/smartart/slide/) | 형상의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides.smartart/smartart/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ko/aspose.slides.smartart/smartart/graphical_object_lock/) | 형상의 잠금을 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/ko/aspose.slides.smartart/smartart/all_nodes/) | SmartArt 객체의 모든 노드 컬렉션을 반환합니다.<br/>            읽기 전용 [`ISmartArtNodeCollection`](/slides/python-net/ko/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/ko/aspose.slides.smartart/smartart/nodes/) | SmartArt 객체의 루트 노드 컬렉션을 반환합니다.<br/>            읽기 전용 [`ISmartArtNodeCollection`](/slides/python-net/ko/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/ko/aspose.slides.smartart/smartart/layout/) | SmartArt 객체의 레이아웃을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`SmartArtLayoutType`](/slides/python-net/ko/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/ko/aspose.slides.smartart/smartart/quick_style/) | SmartArt 객체의 빠른 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`SmartArtQuickStyleType`](/slides/python-net/ko/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/ko/aspose.slides.smartart/smartart/color_style/) | SmartArt 객체의 색상 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`SmartArtColorType`](/slides/python-net/ko/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/ko/aspose.slides.smartart/smartart/is_reversed/) | 다이어그램이 반전을 지원하는 경우 (왼쪽에서 오른쪽) LTR 또는 (오른쪽에서 왼쪽) RTL 상태를 반환하거나 설정합니다.<br/>            읽기/쓰기 **bool**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides.smartart/smartart/get_image/#) | 형상 썸네일을 반환합니다.<br/>            ShapeThumbnailBounds.Shape 형상 썸네일 경계 유형이 기본값으로 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | 형상 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | 형상의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 형상의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides.smartart/smartart/remove_placeholder/#) | 이 형상이 플레이스홀더가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides.smartart/smartart/get_base_placeholder/#) | 기본 플레이스홀더 형상을 반환합니다(현재 형상이 상속받은 레이아웃 및/또는 마스터 슬라이드의 형상).<br/>            현재 형상이 상속받지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides.smartart/smartart/get_visual_bounds/#) | 렌더링된 내용을 기준으로 계산된 형상의 시각적 경계를 가져옵니다. |

### 참고
* 클래스 [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 클래스 [`SmartArt`](/slides/python-net/ko/aspose.slides.smartart/smartart)
* 모듈 [`aspose.slides.smartart`](/slides/python-net/ko/aspose.slides.smartart)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)