---
title: Table class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/table/
---
## Table class

슬라이드에 있는 표를 나타냅니다.

**Inheritance:**[`Table`](/slides/python-net/ko/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

Table 형식은 다음 멤버를 노출합니다:

## Properties

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/table/is_text_holder/) | 모양이 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/table/placeholder/) | 모양에 대한 자리표시자를 반환합니다. 모양에 자리표시자가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/table/custom_data/) | 모양의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/table/raw_frame/) | 원시 모양 프레임의 속성을 가져오거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/table/frame/) | 모양 프레임의 속성을 가져오거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/table/line_format/) | 모양에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 일부 유형의 모양에 대해서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/table/three_d_format/) | 모양에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 일부 유형의 모양에 대해서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/table/effect_format/) | 모양에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 일부 유형의 모양에 대해서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/table/fill_format/) | Table에 대한 채우기 서식을 포함하는 TableFormat.FillFormat 객체를 반환합니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/table/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 가져오거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/table/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 가져오거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/table/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides/table/hidden/) | 모양이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/table/z_order_position/) | z-순서에서 모양의 위치를 반환합니다.<br/>            Shapes[0]은 z-순서에서 가장 뒤에 있는 모양을 반환하고,<br/>            Shapes[Shapes.Count - 1]은 z-순서에서 가장 앞에 있는 모양을 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/table/connection_site_count/) | 모양에 있는 연결 지점의 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/table/rotation/) | 지정된 모양이 z축을 중심으로 회전한 각도를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/table/x/) | 모양의 좌상단 코너의 x좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/table/y/) | 모양의 좌상단 코너의 y좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/table/width/) | 모양의 너비를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/table/height/) | 모양의 높이를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/table/black_white_mode/) | 속성은 모양이 흑백 디스플레이 모드에서 어떻게 렌더링될지를 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/table/unique_id/) | 추가 기능이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다.<br/>            이 값은 사용자가 또는 프로그래밍을 통해 재할당될 수 있으므로, 지속적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id)를 참조하십시오. |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/table/office_interop_shape_id/) | 슬라이드 범위의 고유 식별자를 반환하며, 이는 모양의 수명 동안 일정하게 유지되어 PowerPoint 또는 인터옵 코드가 문서 어디에서든 모양을 신뢰성 있게 참조할 수 있게 합니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id)를 참조하십시오. |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/table/alternative_text/) | 모양과 연관된 대체 텍스트를 가져오거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/table/alternative_text_title/) | 모양과 연관된 대체 텍스트의 제목을 가져오거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/table/name/) | 모양의 이름을 가져오거나 설정합니다.<br/>            None이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/table/is_decorative/) | 'Mark as decorative' 옵션을 가져오거나 설정합니다<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/table/shape_lock/) | 모양의 잠금을 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/table/is_grouped/) | 모양이 그룹화되었는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides/table/parent_group/) | 모양이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/table/slide/) | 모양의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/table/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ko/aspose.slides/table/graphical_object_lock/) | 모양의 잠금을 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/ko/aspose.slides/table/rows/) | 행 컬렉션을 반환합니다.<br/>            읽기 전용 [`IRowCollection`](/slides/python-net/ko/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/ko/aspose.slides/table/columns/) | 열 컬렉션을 반환합니다.<br/>            읽기 전용 [`IColumnCollection`](/slides/python-net/ko/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/ko/aspose.slides/table/table_format/) | 이 테이블에 대한 서식 속성을 포함하는 TableFormat 객체를 반환합니다.<br/>            읽기 전용 [`ITableFormat`](/slides/python-net/ko/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/ko/aspose.slides/table/style_preset/) | 내장 테이블 스타일을 가져오거나 설정합니다.<br/>            읽기/쓰기 [`TableStylePreset`](/slides/python-net/ko/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/ko/aspose.slides/table/right_to_left/) | 테이블이 오른쪽에서 왼쪽으로 읽는 순서를 갖는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`first_row`](/slides/python-net/ko/aspose.slides/table/first_row/) | 테이블의 첫 번째 행을 특수 서식으로 그릴지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`first_col`](/slides/python-net/ko/aspose.slides/table/first_col/) | 테이블의 첫 번째 열을 특수 서식으로 그릴지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`last_row`](/slides/python-net/ko/aspose.slides/table/last_row/) | 테이블의 마지막 행을 특수 서식으로 그릴지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`last_col`](/slides/python-net/ko/aspose.slides/table/last_col/) | 테이블의 마지막 열을 특수 서식으로 그릴지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`horizontal_banding`](/slides/python-net/ko/aspose.slides/table/horizontal_banding/) | 짝수 행을 다른 서식으로 그릴지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`vertical_banding`](/slides/python-net/ko/aspose.slides/table/vertical_banding/) | 짝수 열을 다른 서식으로 그릴지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |

## Methods

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/table/get_image/#) | 모양 썸네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape 모양 썸네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | 모양 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/table/write_as_svg/#iorawiobase) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`set_text_format(self, source)`](/slides/python-net/ko/aspose.slides/table/set_text_format/#iportionformat) | 정의된 구역 서식 속성을 모든 표 셀의 구역에 적용합니다. |
| [`set_text_format(self, source)`](/slides/python-net/ko/aspose.slides/table/set_text_format/#iparagraphformat) | 정의된 단락 서식 속성을 모든 표 셀의 단락에 적용합니다. |
| [`set_text_format(self, source)`](/slides/python-net/ko/aspose.slides/table/set_text_format/#itextframeformat) | 정의된 텍스트 프레임 서식 속성을 모든 표 셀의 텍스트 프레임에 적용합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/table/remove_placeholder/#) | 이 모양이 자리표시자가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/table/add_placeholder/#iplaceholder) | 자리표시자가 없을 경우 새 자리표시자를 추가하고 지정된 자리표시자에 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/table/get_base_placeholder/#) | 기본 자리표시자 모양을 반환합니다(현재 모양이 상속받은 레이아웃 및/또는 마스터 슬라이드의 모양).<br/>            현재 모양이 상속받지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides/table/get_visual_bounds/#) | 렌더링된 콘텐츠에서 계산된 모양의 시각적 경계를 가져옵니다. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/ko/aspose.slides/table/merge_cells/#icell-icell-bool) | 인접 셀을 병합합니다. |

### See Also
* class [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject)
* class [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* class [`Table`](/slides/python-net/ko/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)