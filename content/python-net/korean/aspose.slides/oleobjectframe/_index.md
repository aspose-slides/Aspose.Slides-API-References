---
title: OleObjectFrame class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/oleobjectframe/
---
## OleObjectFrame 클래스

Represents an OLE object on a slide.

**Inheritance:**[`OleObjectFrame`](/slides/python-net/ko/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

The OleObjectFrame type exposes the following members:

## 속성

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/oleobjectframe/is_text_holder/) | 모양이 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/oleobjectframe/placeholder/) | 모양의 자리 표시자를 반환합니다. 모양에 자리 표시자가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/oleobjectframe/custom_data/) | 모양의 사용자 지정 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/oleobjectframe/raw_frame/) | 원시 모양 프레임 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/oleobjectframe/frame/) | 모양 프레임 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/oleobjectframe/line_format/) | 모양의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 모양 유형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/oleobjectframe/three_d_format/) | 모양의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 모양 유형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/oleobjectframe/effect_format/) | 모양에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 모양 유형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/oleobjectframe/fill_format/) | 모양의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 모양 유형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/oleobjectframe/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/oleobjectframe/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides/oleobjectframe/hidden/) | 모양이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/oleobjectframe/z_order_position/) | z-순서에서 모양의 위치를 반환합니다.<br/>            Shapes[0]은 z-순서 뒤쪽에 있는 모양을 반환하고,<br/>            Shapes[Shapes.Count - 1]은 앞쪽에 있는 모양을 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/oleobjectframe/connection_site_count/) | 모양의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/oleobjectframe/rotation/) | 지정된 모양이 z축을 중심으로 회전한 각도(도)를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/oleobjectframe/x/) | 모양 왼쪽 위 모서리의 x좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/oleobjectframe/y/) | 모양 왼쪽 위 모서리의 y좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/oleobjectframe/width/) | 모양의 너비를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/oleobjectframe/height/) | 모양의 높이를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/oleobjectframe/black_white_mode/) | 속성은 모양이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/oleobjectframe/unique_id/) | 애드인 또는 기타 코드에서 사용하도록 설계된 프레젠테이션 범위의 내부 식별자를 반환합니다.<br/>            이 값은 사용자 또는 프로그래밍으로 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id)을(를) 참조하십시오. |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/oleobjectframe/office_interop_shape_id/) | 슬라이드 범위의 고유 식별자를 반환하며, 이 식별자는 모양의 수명 동안 일정하게 유지되고 문서 어디서든 PowerPoint 혹은 인터옵 코드가 모양을 안정적으로 참조할 수 있게 합니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id)을(를) 참조하십시오. |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/oleobjectframe/alternative_text/) | 모양과 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/oleobjectframe/alternative_text_title/) | 모양과 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/oleobjectframe/name/) | 모양의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/oleobjectframe/is_decorative/) | '장식으로 표시' 옵션을 가져오거나 설정합니다<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/oleobjectframe/shape_lock/) | 모양의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/oleobjectframe/is_grouped/) | 모양이 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides/oleobjectframe/parent_group/) | 모양이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/oleobjectframe/slide/) | 모양의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/oleobjectframe/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ko/aspose.slides/oleobjectframe/graphical_object_lock/) | 모양의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/ko/aspose.slides/oleobjectframe/substitute_picture_format/) | OleObject 이미지 채우기 속성 객체를 반환합니다.<br/>            읽기 전용 [`IPictureFillFormat`](/slides/python-net/ko/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/ko/aspose.slides/oleobjectframe/substitute_picture_title/) | OleObject 아이콘의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`object_name`](/slides/python-net/ko/aspose.slides/oleobjectframe/object_name/) | 객체의 이름을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`object_prog_id`](/slides/python-net/ko/aspose.slides/oleobjectframe/object_prog_id/) | 객체의 ProgID를 반환합니다.<br/>            읽기 전용 **str**. |
| [`link_file_name`](/slides/python-net/ko/aspose.slides/oleobjectframe/link_file_name/) | 연결된 파일의 전체 경로를 반환합니다. 짧은 파일 이름이 사용됩니다.<br/>            읽기 전용 **str**. |
| [`link_path_long`](/slides/python-net/ko/aspose.slides/oleobjectframe/link_path_long/) | 연결된 파일의 전체 경로를 반환합니다. 긴 파일 이름이 사용됩니다.<br/>            읽기/쓰기 **str**. |
| [`link_path_relative`](/slides/python-net/ko/aspose.slides/oleobjectframe/link_path_relative/) | 존재하는 경우 연결된 파일의 상대 경로를 반환하고, 없으면 빈 문자열을 반환합니다.<br/>             읽기 전용 **str**. |
| [`embedded_file_label`](/slides/python-net/ko/aspose.slides/oleobjectframe/embedded_file_label/) | 포함된 OLE 객체의 파일 이름을 반환합니다 |
| [`embedded_file_name`](/slides/python-net/ko/aspose.slides/oleobjectframe/embedded_file_name/) | 포함된 OLE 객체의 경로를 반환합니다 |
| [`embedded_data`](/slides/python-net/ko/aspose.slides/oleobjectframe/embedded_data/) | OLE 포함 데이터에 대한 정보를 가져오거나 설정합니다.<br/>            읽기/쓰기 [`IOleEmbeddedDataInfo`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/ko/aspose.slides/oleobjectframe/is_object_icon/) | 객체가 아이콘으로 표시되는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`is_object_link`](/slides/python-net/ko/aspose.slides/oleobjectframe/is_object_link/) | 객체가 외부 파일에 연결되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`update_automatic`](/slides/python-net/ko/aspose.slides/oleobjectframe/update_automatic/) | 프레젠테이션을 열거나 인쇄할 때 연결된 포함 객체가 자동으로 업데이트되는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/oleobjectframe/get_image/#) | 모양 썸네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape 모양 썸네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | 모양 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/oleobjectframe/remove_placeholder/#) | 이 모양이 자리 표시자가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | 자리 표시자가 없을 경우 새 자리 표시자를 추가하고 지정된 자리 표시자 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/oleobjectframe/get_base_placeholder/#) | 기본 자리 표시자 모양을 반환합니다(현재 모양이 상속받은 레이아웃 및/또는 마스터 슬라이드의 모양).<br/>            현재 모양이 상속받지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides/oleobjectframe/get_visual_bounds/#) | 렌더링된 내용으로부터 계산된 모양의 시각적 경계를 가져옵니다. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/ko/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | OLE 포함 데이터에 대한 정보를 설정합니다.<br/>            <br/>            이 메서드는 객체의 속성을 새로운 데이터에 맞게 변경하고 <br/>            IsObjectLink 플래그를 false로 설정하여 OLE 객체가 포함됨을 나타냅니다. |

### 참고
* 클래스 [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject)
* 클래스 [`OleObjectFrame`](/slides/python-net/ko/aspose.slides/oleobjectframe)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)