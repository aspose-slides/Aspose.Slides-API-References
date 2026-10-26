---
title: VideoFrame class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/videoframe/
---
## VideoFrame 클래스

슬라이드에 있는 비디오 클립을 나타냅니다.

**상속:**[`VideoFrame`](/slides/python-net/ko/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/ko/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

VideoFrame 타입은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/videoframe/is_text_holder/) | 형식이 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/videoframe/placeholder/) | 형식에 대한 자리 표시자를 반환합니다. 형식에 자리 표시자가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/videoframe/custom_data/) | 형식의 사용자 지정 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/videoframe/raw_frame/) | 원시 형식 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/videoframe/frame/) | 형식 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/videoframe/line_format/) | 형식에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 형태에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/videoframe/three_d_format/) | 형식에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 형태에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/videoframe/effect_format/) | 형식에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 형태에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/videoframe/fill_format/) | 형식에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 형태에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/videoframe/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/videoframe/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/videoframe/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides/videoframe/hidden/) | 형식이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/videoframe/z_order_position/) | z-순서에서 형식의 위치를 반환합니다.<br/>            Shapes[0]은 z-순서의 뒤쪽에 있는 형식을 반환하고,<br/>            Shapes[Shapes.Count - 1]은 z-순서의 앞쪽에 있는 형식을 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/videoframe/connection_site_count/) | 형식의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/videoframe/rotation/) | 지정된 형식이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/videoframe/x/) | 형식의 왼쪽 위 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/videoframe/y/) | 형식의 왼쪽 위 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/videoframe/width/) | 형식의 너비를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/videoframe/height/) | 형식의 높이를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/videoframe/black_white_mode/) | 속성은 형식이 흑백 디스플레이 모드에서 어떻게 렌더링되는지를 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/videoframe/unique_id/) | 애드인이나 기타 코드에서 사용하도록 의도된 내부 프레젠테이션 범위 식별자를 반환합니다.<br/>            이 값은 사용자 또는 프로그래밍 방식으로 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id)를 참조하십시오. |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/videoframe/office_interop_shape_id/) | 형식의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, 이를 통해 PowerPoint 또는 인터롭 코드가 문서 어디서든 형식을 신뢰성 있게 참조할 수 있습니다.<br/>            읽기 전용 **int**.<br/>            또한 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id)를 참조하십시오. |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/videoframe/alternative_text/) | 형식에 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/videoframe/alternative_text_title/) | 형식에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/videoframe/name/) | 형식의 이름을 반환하거나 설정합니다.<br/>            None이면 안 됩니다. 필요하다면 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/videoframe/is_decorative/) | ‘장식용으로 표시’ 옵션을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/videoframe/shape_lock/) | 형식의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IPictureFrameLock`](/slides/python-net/ko/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/videoframe/is_grouped/) | 형식이 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides/videoframe/parent_group/) | 형식이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/videoframe/slide/) | 형식의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/videoframe/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ko/aspose.slides/videoframe/shape_style/) | 형식의 스타일 객체를 반환합니다.<br/>            읽기 전용 [`IShapeStyle`](/slides/python-net/ko/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ko/aspose.slides/videoframe/shape_type/) | PictureFrame에 대한 AutoShape 타입을 반환하거나 설정합니다.<br/>            허용되는 모든 항목은 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) 집합에 포함되어 있으며, 다음과 같은 모든 종류의 라인은 제외됩니다:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            읽기/쓰기 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ko/aspose.slides/videoframe/adjustments/) | 형식의 조정 값 컬렉션을 반환합니다.<br/>            읽기 전용 [`IAdjustValueCollection`](/slides/python-net/ko/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ko/aspose.slides/videoframe/picture_frame_lock/) | 형식의 잠금 상태를 반환합니다.<br/>            읽기 전용 [`IPictureFrameLock`](/slides/python-net/ko/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ko/aspose.slides/videoframe/picture_format/) | 그림 프레임에 대한 PictureFillFormat 객체를 반환합니다.<br/>            읽기 전용 [`IPictureFillFormat`](/slides/python-net/ko/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ko/aspose.slides/videoframe/relative_scale_height/) | 그림 프레임의 높이 비율(원본 그림 크기에 대한 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다.<br/>            읽기/쓰기 **float**. |
| [`relative_scale_width`](/slides/python-net/ko/aspose.slides/videoframe/relative_scale_width/) | 그림 프레임의 너비 비율(원본 그림 크기에 대한 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다.<br/>            읽기/쓰기 **float**. |
| [`is_cameo`](/slides/python-net/ko/aspose.slides/videoframe/is_cameo/) | PictureFrame이 Cameo 객체인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`rewind_video`](/slides/python-net/ko/aspose.slides/videoframe/rewind_video/) | 동영상이 재생이 끝나자마자 자동으로 시작 부분으로 되돌아가는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`play_loop_mode`](/slides/python-net/ko/aspose.slides/videoframe/play_loop_mode/) | 동영상이 반복 재생되는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`hide_at_showing`](/slides/python-net/ko/aspose.slides/videoframe/hide_at_showing/) | VideoFrame이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`volume`](/slides/python-net/ko/aspose.slides/videoframe/volume/) | 오디오 볼륨을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`AudioVolumeMode`](/slides/python-net/ko/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/ko/aspose.slides/videoframe/play_mode/) | 동영상 재생 모드를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`VideoPlayModePreset`](/slides/python-net/ko/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/ko/aspose.slides/videoframe/full_screen_mode/) | 동영상이 전체 화면 모드에서 표시되는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`link_path_long`](/slides/python-net/ko/aspose.slides/videoframe/link_path_long/) | VideoFrame에 연결된 비디오 파일 이름을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`embedded_video`](/slides/python-net/ko/aspose.slides/videoframe/embedded_video/) | 임베드된 비디오 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IVideo`](/slides/python-net/ko/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/ko/aspose.slides/videoframe/trim_from_start/) | 시작 트림 [ms] |
| [`trim_from_end`](/slides/python-net/ko/aspose.slides/videoframe/trim_from_end/) | 끝 트림 [ms] |
| [`caption_tracks`](/slides/python-net/ko/aspose.slides/videoframe/caption_tracks/) | 비디오 프레임과 연결된 폐쇄 캡션 컬렉션을 가져옵니다.<br/>            이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [`ICaptionsCollection`](/slides/python-net/ko/aspose.slides/icaptionscollection)를 반환합니다. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/videoframe/get_image/#) | 형식 썸네일을 반환합니다.<br/>            ShapeThumbnailBounds.Shape 형식 썸네일 경계 타입이 기본값으로 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | 형식 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/videoframe/write_as_svg/#iorawiobase) | 형식의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 형식의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/videoframe/remove_placeholder/#) | 이 형식이 자리 표시자가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/videoframe/add_placeholder/#iplaceholder) | 자리 표시자가 없으면 새 자리 표시자를 추가하고 지정된 자리 표시자 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/videoframe/get_base_placeholder/#) | 기본 자리 표시자 형식을 반환합니다(현재 형식이 상속받은 레이아웃 및/또는 마스터 슬라이드의 형식).<br/>            현재 형식이 상속받지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides/videoframe/get_visual_bounds/#) | 렌더링된 내용으로 계산된 형식의 시각적 경계를 가져옵니다. |
| [`get_geometry_paths(self)`](/slides/python-net/ko/aspose.slides/videoframe/get_geometry_paths/#) | 기하학 형식 경로의 복사본을 반환합니다. 좌표는 형식의 좌상단 모서리를 기준으로 합니다. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ko/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 객체에서 형식 기하학을 업데이트합니다. 좌표는 형식의 좌상단 모서리를 기준이어야 합니다.<br/>             형식의 타입([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)로 변경합니다. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ko/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 배열에서 형식 기하학을 업데이트합니다. 좌표는 형식의 좌상단 모서리를 기준이어야 합니다.<br/>             형식의 타입([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)로 변경합니다. |
| [`create_shape_elements(self)`](/slides/python-net/ko/aspose.slides/videoframe/create_shape_elements/#) | 형식 요소 배열을 생성하고 반환합니다. |

### 참고
* 클래스 [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape)
* 클래스 [`PictureFrame`](/slides/python-net/ko/aspose.slides/pictureframe)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 클래스 [`VideoFrame`](/slides/python-net/ko/aspose.slides/videoframe)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)