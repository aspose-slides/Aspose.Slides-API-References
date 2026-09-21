---
title: Connector class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/connector/
---
## Connector 클래스

Represents a connector.

**Inheritance:**[`Connector`](/slides/python-net/ko/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

The Connector type exposes the following members:

## 속성

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/connector/is_text_holder/) | 도형이 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/connector/placeholder/) | 도형에 대한 플레이스홀더를 반환합니다. 도형에 플레이스홀더가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/connector/custom_data/) | 도형의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/connector/raw_frame/) | 원시 도형 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/connector/frame/) | 도형 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/connector/line_format/) | 도형에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 유형의 도형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/connector/three_d_format/) | 도형에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 유형의 도형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/connector/effect_format/) | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 유형의 도형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/connector/fill_format/) | 도형에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 유형의 도형에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/connector/hyperlink_click/) | 마우스 클릭에 대한 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/connector/hyperlink_mouse_over/) | 마우스 오버에 대한 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/connector/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides/connector/hidden/) | 도형이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/connector/z_order_position/) | 도형의 z-순서 내 위치를 반환합니다.<br/>            Shapes[0]은 z-순서의 뒤쪽에 있는 도형을 반환하고,<br/>            Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/connector/connection_site_count/) | 도형의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/connector/rotation/) | 지정된 도형이 z축을 중심으로 회전한 각도를 반환하거나 설정합니다.<br/>            양수값은 시계 방향 회전을 나타내고, 음수값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/connector/x/) | 도형의 왼쪽 위 모서리의 x좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/connector/y/) | 도형의 왼쪽 위 모서리의 y좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/connector/width/) | 도형의 너비를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/connector/height/) | 도형의 높이를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/connector/black_white_mode/) | 속성은 도형이 흑백 디스플레이 모드에서 어떻게 렌더링될지 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/connector/unique_id/) | 애드인이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다.<br/>            이 값은 사용자에 의해 또는 프로그래밍 방식으로 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id)을 참조하십시오. |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/connector/office_interop_shape_id/) | 도형의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며,<br/>            PowerPoint 또는 인터롭 코드를 통해 문서 어디에서든 도형을 신뢰성 있게 참조할 수 있게 합니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id)을 참조하십시오. |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/connector/alternative_text/) | 도형에 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/connector/alternative_text_title/) | 도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/connector/name/) | 도형의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/connector/is_decorative/) | ‘장식으로 표시’ 옵션을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/connector/shape_lock/) | 도형의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IConnectorLock`](/slides/python-net/ko/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/connector/is_grouped/) | 도형이 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides/connector/parent_group/) | 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/connector/slide/) | 도형의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/connector/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ko/aspose.slides/connector/shape_style/) | 도형의 스타일 객체를 반환합니다.<br/>            읽기 전용 [`IShapeStyle`](/slides/python-net/ko/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ko/aspose.slides/connector/shape_type/) | AutoShape 유형을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ko/aspose.slides/connector/adjustments/) | 도형의 조정 값 컬렉션을 반환합니다.<br/>            읽기 전용 [`IAdjustValueCollection`](/slides/python-net/ko/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/ko/aspose.slides/connector/connector_lock/) | 커넥터의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IConnectorLock`](/slides/python-net/ko/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/ko/aspose.slides/connector/start_shape_connected_to/) | 커넥터 시작을 연결할 도형을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/ko/aspose.slides/connector/end_shape_connected_to/) | 커넥터 끝을 연결할 도형을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/ko/aspose.slides/connector/start_shape_connection_site_index/) | 시작 도형의 연결 지점 인덱스를 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/ko/aspose.slides/connector/end_shape_connection_site_index/) | 끝 도형의 연결 지점 인덱스를 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/connector/get_image/#) | 도형 썸네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | 도형 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/connector/write_as_svg/#iorawiobase) | 도형의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 도형의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/connector/remove_placeholder/#) | 이 도형이 플레이스홀더가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/connector/add_placeholder/#iplaceholder) | 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/connector/get_base_placeholder/#) | 기본 플레이스홀더 도형을 반환합니다(현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 도형).<br/>            현재 도형이 상속받지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides/connector/get_visual_bounds/#) | 렌더링된 콘텐츠를 기반으로 계산된 도형의 시각적 경계를 가져옵니다. |
| [`get_geometry_paths(self)`](/slides/python-net/ko/aspose.slides/connector/get_geometry_paths/#) | 기하학 도형 경로의 복사본을 반환합니다. 좌표는 도형의 왼쪽 상단 모서를 기준으로 합니다. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ko/aspose.slides/connector/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 객체를 사용해 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽<br/>             상단 모서를 기준으로 해야 합니다.<br/>             도형 유형([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)(으)로 변경합니다. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ko/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 배열을 사용해 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽<br/>             상단 모서를 기준으로 해야 합니다.<br/>             도형 유형([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)(으)로 변경합니다. |
| [`create_shape_elements(self)`](/slides/python-net/ko/aspose.slides/connector/create_shape_elements/#) | 도형 요소들의 배열을 생성하고 반환합니다. |
| [`reroute(self)`](/slides/python-net/ko/aspose.slides/connector/reroute/#) | 커넥터를 재배치하여 연결된 도형들 사이의 최단 경로를 취하도록 합니다. |

### 참조
* 클래스 [`Connector`](/slides/python-net/ko/aspose.slides/connector)
* 클래스 [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)