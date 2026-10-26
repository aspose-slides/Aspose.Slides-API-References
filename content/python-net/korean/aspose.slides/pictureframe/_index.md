---
title: PictureFrame class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/pictureframe/
---
## PictureFrame 클래스

그 안에 그림이 포함된 프레임을 나타냅니다.

**상속:**[`PictureFrame`](/slides/python-net/ko/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

PictureFrame 유형은 다음 멤버를 노출합니다:

## Properties

| 속성 | 설명 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/pictureframe/is_text_holder/) | 모양이 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/pictureframe/placeholder/) | 모양에 대한 자리표시자를 반환합니다. 모양에 자리표시자가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/pictureframe/custom_data/) | 모양의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/pictureframe/raw_frame/) | 원시 모양 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/pictureframe/frame/) | 모양 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/pictureframe/line_format/) | 모양에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 유형의 모양에 대해서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/pictureframe/three_d_format/) | 모양에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 유형의 모양에 대해서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/pictureframe/effect_format/) | 모양에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 유형의 모양에 대해서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/pictureframe/fill_format/) | 모양에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 유형의 모양에 대해서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/pictureframe/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/pictureframe/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/pictureframe/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides/pictureframe/hidden/) | 모양이 숨겨졌는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/pictureframe/z_order_position/) | z-순서에서 모양의 위치를 반환합니다.<br/>            Shapes[0]은 z-순서의 뒤쪽에 있는 모양을 반환하고,<br/>            Shapes[Shapes.Count - 1]은 앞쪽에 있는 모양을 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/pictureframe/connection_site_count/) | 모양의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/pictureframe/rotation/) | 지정된 모양이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/pictureframe/x/) | 포인트 단위로 측정된 모양의 왼쪽 위 모서리 x 좌표를 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/pictureframe/y/) | 포인트 단위로 측정된 모양의 왼쪽 위 모서리 y 좌표를 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/pictureframe/width/) | 포인트 단위로 측정된 모양의 너비를 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/pictureframe/height/) | 포인트 단위로 측정된 모양의 높이를 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/pictureframe/black_white_mode/) | 속성은 모양이 흑백 디스플레이 모드에서 어떻게 렌더링될지를 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/pictureframe/unique_id/) | 애드인이나 기타 코드에서 사용하도록 설계된 프레젠테이션 범위 내부 식별자를 반환합니다.<br/>            이 값은 사용자에 의해 또는 프로그래밍 방식으로 재지정될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id)을 참조하십시오. |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/pictureframe/office_interop_shape_id/) | 모양의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, 이를 통해 PowerPoint 또는 interop 코드가 문서 어디서든 모양을 안정적으로 참조할 수 있습니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id)을 참조하십시오. |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/pictureframe/alternative_text/) | 모양에 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/pictureframe/alternative_text_title/) | 모양에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/pictureframe/name/) | 모양의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/pictureframe/is_decorative/) | ‘장식용으로 표시’ 옵션을 가져오거나 설정합니다<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/pictureframe/shape_lock/) | 모양의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IPictureFrameLock`](/slides/python-net/ko/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/pictureframe/is_grouped/) | 모양이 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides/pictureframe/parent_group/) | 모양이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/pictureframe/slide/) | 모양의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/pictureframe/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ko/aspose.slides/pictureframe/shape_style/) | 모양의 스타일 객체를 반환합니다.<br/>            읽기 전용 [`IShapeStyle`](/slides/python-net/ko/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ko/aspose.slides/pictureframe/shape_type/) | PictureFrame의 AutoShape 유형을 반환하거나 설정합니다.<br/>            허용되는 모든 항목은 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) 집합에 포함되어 있으며,<br/>            다음과 같은 모든 종류의 선은 제외됩니다:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            읽기/쓰기 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ko/aspose.slides/pictureframe/adjustments/) | 모양의 조정 값 컬렉션을 반환합니다.<br/>            읽기 전용 [`IAdjustValueCollection`](/slides/python-net/ko/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ko/aspose.slides/pictureframe/picture_frame_lock/) | 모양의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IPictureFrameLock`](/slides/python-net/ko/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ko/aspose.slides/pictureframe/picture_format/) | PictureFrame에 대한 PictureFillFormat 객체를 반환합니다.<br/>            읽기 전용 [`IPictureFillFormat`](/slides/python-net/ko/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ko/aspose.slides/pictureframe/relative_scale_height/) | PictureFrame의 높이 비율(원본 그림 크기에 대한 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다.<br/>            읽기/쓰기 **float**. |
| [`relative_scale_width`](/slides/python-net/ko/aspose.slides/pictureframe/relative_scale_width/) | PictureFrame의 너비 비율(원본 그림 크기에 대한 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다.<br/>            읽기/쓰기 **float**. |
| [`is_cameo`](/slides/python-net/ko/aspose.slides/pictureframe/is_cameo/) | PictureFrame이 Cameo 객체인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |

## Methods

| 메서드 | 설명 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/pictureframe/get_image/#) | 모양 썸네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape 모양 썸네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | 모양 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/pictureframe/remove_placeholder/#) | 이 모양이 자리표시자가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | 새 자리표시자가 없을 경우 추가하고 지정된 자리표시자 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/pictureframe/get_base_placeholder/#) | 기본 자리표시자 모양을 반환합니다(현재 모양이 상속받은 레이아웃 및/또는 마스터 슬라이드의 모양).<br/>            현재 모양이 상속받지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides/pictureframe/get_visual_bounds/#) | 렌더링된 콘텐츠를 기반으로 계산된 모양의 시각적 경계를 가져옵니다. |
| [`get_geometry_paths(self)`](/slides/python-net/ko/aspose.slides/pictureframe/get_geometry_paths/#) | 지오메트리 모양의 경로 복사본을 반환합니다. 좌표는 모양의 왼쪽 위 모서리를 기준으로 합니다. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ko/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 객체에서 모양 지오메트리를 업데이트합니다. 좌표는 모양의 왼쪽 위 모서리를 기준으로 해야 합니다.<br/>             모양 유형을 ([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))에서 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)으로 변경합니다. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ko/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 배열에서 모양 지오메트리를 업데이트합니다. 좌표는 모양의 왼쪽 위 모서리를 기준으로 해야 합니다.<br/>             모양 유형을 ([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))에서 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)으로 변경합니다. |
| [`create_shape_elements(self)`](/slides/python-net/ko/aspose.slides/pictureframe/create_shape_elements/#) | 모양 요소들의 배열을 생성하고 반환합니다. |

### 참조
* 클래스 [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape)
* 클래스 [`PictureFrame`](/slides/python-net/ko/aspose.slides/pictureframe)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)