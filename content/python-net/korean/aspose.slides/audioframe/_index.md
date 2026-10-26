---
title: AudioFrame class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/audioframe/
---
## AudioFrame 클래스

슬라이드의 오디오 클립을 나타냅니다.

**Inheritance:**[`AudioFrame`](/slides/python-net/ko/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/ko/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

AudioFrame 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/audioframe/is_text_holder/) | shape이 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides/audioframe/placeholder/) | shape의 자리표시자를 반환합니다. shape에 자리표시자가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/audioframe/custom_data/) | shape의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/audioframe/raw_frame/) | 원시 shape 프레임 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides/audioframe/frame/) | shape 프레임 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides/audioframe/line_format/) | shape의 선 형식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 유형의 shape에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/audioframe/three_d_format/) | shape의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 유형의 shape에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/audioframe/effect_format/) | shape에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 유형의 shape에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/audioframe/fill_format/) | shape의 채우기 형식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 유형의 shape에 대해 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/audioframe/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/audioframe/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/audioframe/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides/audioframe/hidden/) | shape이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/audioframe/z_order_position/) | shape의 z-순서에서 위치를 반환합니다.<br/>            Shapes[0]은 z-순서 뒤쪽에 있는 shape를 반환하고,<br/>            Shapes[Shapes.Count - 1]은 z-순서 앞쪽에 있는 shape를 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/audioframe/connection_site_count/) | shape의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides/audioframe/rotation/) | 지정된 shape가 z축을 중심으로 회전하는 각도(도)를 반환하거나 설정합니다.<br/>            양수값은 시계 방향 회전을 나타내고, 음수값은 반시계 방향 회전을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides/audioframe/x/) | shape의 왼쪽 위 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/audioframe/y/) | shape의 왼쪽 위 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/audioframe/width/) | shape의 너비를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/audioframe/height/) | shape의 높이를 포인트 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/audioframe/black_white_mode/) | 속성은 shape가 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides/audioframe/unique_id/) | 애드인이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다.<br/>            이 값은 사용자나 프로그램에 의해 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            또 참조: [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/audioframe/office_interop_shape_id/) | shape의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하고,<br/>            PowerPoint 또는 인터옵 코드가 문서 어디에서든 shape를 신뢰성 있게 참조할 수 있게 합니다.<br/>            읽기 전용 **int**.<br/>            또 참조: [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/audioframe/alternative_text/) | shape와 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/audioframe/alternative_text_title/) | shape와 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides/audioframe/name/) | shape의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요에 따라 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/audioframe/is_decorative/) | ‘Mark as decorative’ 옵션을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/audioframe/shape_lock/) | shape의 잠금을 반환합니다.<br/>            읽기 전용 [`IPictureFrameLock`](/slides/python-net/ko/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/audioframe/is_grouped/) | shape가 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides/audioframe/parent_group/) | shape가 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides/audioframe/slide/) | shape의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/audioframe/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ko/aspose.slides/audioframe/shape_style/) | shape의 스타일 객체를 반환합니다.<br/>            읽기 전용 [`IShapeStyle`](/slides/python-net/ko/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ko/aspose.slides/audioframe/shape_type/) | PictureFrame의 AutoShape 유형을 반환하거나 설정합니다.<br/>            허용되는 모든 항목은 집합 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)에 포함되며,<br/>            단선 종류는 제외합니다:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            읽기/쓰기 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ko/aspose.slides/audioframe/adjustments/) | shape의 조정값 컬렉션을 반환합니다.<br/>            읽기 전용 [`IAdjustValueCollection`](/slides/python-net/ko/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ko/aspose.slides/audioframe/picture_frame_lock/) | shape의 잠금을 반환합니다.<br/>            읽기 전용 [`IPictureFrameLock`](/slides/python-net/ko/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ko/aspose.slides/audioframe/picture_format/) | picture frame의 PictureFillFormat 객체를 반환합니다.<br/>            읽기 전용 [`IPictureFillFormat`](/slides/python-net/ko/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ko/aspose.slides/audioframe/relative_scale_height/) | picture frame의 높이 비율(원본 이미지 크기에 대한)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다.<br/>            읽기/쓰기 **float**. |
| [`relative_scale_width`](/slides/python-net/ko/aspose.slides/audioframe/relative_scale_width/) | picture frame의 너비 비율(원본 이미지 크기에 대한)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다.<br/>            읽기/쓰기 **float**. |
| [`is_cameo`](/slides/python-net/ko/aspose.slides/audioframe/is_cameo/) | PictureFrame이 Cameo 객체인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`audio_cd_start_track`](/slides/python-net/ko/aspose.slides/audioframe/audio_cd_start_track/) | 시작 트랙 인덱스를 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/ko/aspose.slides/audioframe/audio_cd_start_track_time/) | 시작 트랙 시간을 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`audio_cd_end_track`](/slides/python-net/ko/aspose.slides/audioframe/audio_cd_end_track/) | 마지막 트랙 인덱스를 반환하거나 설정합니다<br/>            읽기/쓰기 **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/ko/aspose.slides/audioframe/audio_cd_end_track_time/) | 마지막 트랙 시간을 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`volume`](/slides/python-net/ko/aspose.slides/audioframe/volume/) | 오디오 볼륨을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`AudioVolumeMode`](/slides/python-net/ko/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/ko/aspose.slides/audioframe/play_mode/) | 오디오 재생 모드를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`AudioPlayModePreset`](/slides/python-net/ko/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/ko/aspose.slides/audioframe/hide_at_showing/) | AudioFrame이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`play_loop_mode`](/slides/python-net/ko/aspose.slides/audioframe/play_loop_mode/) | 오디오가 반복 재생되는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`play_across_slides`](/slides/python-net/ko/aspose.slides/audioframe/play_across_slides/) | 오디오가 슬라이드 전반에 걸쳐 재생되는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`rewind_audio`](/slides/python-net/ko/aspose.slides/audioframe/rewind_audio/) | 오디오가 재생 후 자동으로 시작으로 되감기 되는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`embedded`](/slides/python-net/ko/aspose.slides/audioframe/embedded/) | 사운드가 프레젠테이션에 포함되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`link_path_long`](/slides/python-net/ko/aspose.slides/audioframe/link_path_long/) | AudioFrame에 연결된 오디오 파일 이름을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`embedded_audio`](/slides/python-net/ko/aspose.slides/audioframe/embedded_audio/) | 임베디드 오디오 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/ko/aspose.slides/audioframe/fade_in_duration/) | 미디어의 초기 페이드 인 지속 시간을 밀리초 단위로 지정합니다.<br/>            읽기/쓰기 **float**. |
| [`fade_out_duration`](/slides/python-net/ko/aspose.slides/audioframe/fade_out_duration/) | 미디어의 종료 페이드 아웃 지속 시간을 밀리초 단위로 지정합니다.<br/>            읽기/쓰기 **float**. |
| [`volume_value`](/slides/python-net/ko/aspose.slides/audioframe/volume_value/) | 오디오 볼륨을 퍼센트로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`trim_from_start`](/slides/python-net/ko/aspose.slides/audioframe/trim_from_start/) | 재생 중 미디어 시작 부분에서 제거할 지속 시간을 밀리초 단위로 지정합니다.<br/>            읽기/쓰기 **float**. |
| [`trim_from_end`](/slides/python-net/ko/aspose.slides/audioframe/trim_from_end/) | 재생 중 미디어 끝 부분에서 제거할 지속 시간을 밀리초 단위로 지정합니다.<br/>            읽기/쓰기 **float**. |
| [`caption_tracks`](/slides/python-net/ko/aspose.slides/audioframe/caption_tracks/) | 오디오 프레임에 연결된 폐쇄 캡션 컬렉션을 가져옵니다.<br/>            이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [`ICaptionsCollection`](/slides/python-net/ko/aspose.slides/icaptionscollection)를 반환합니다. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/audioframe/get_image/#) | shape 썸네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape shape 썸네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | shape 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/audioframe/remove_placeholder/#) | 이 shape가 자리표시자가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/audioframe/add_placeholder/#iplaceholder) | 자리표시자가 없을 경우 새 자리표시자를 추가하고 지정된 자리표시자 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/audioframe/get_base_placeholder/#) | 기본 자리표시자 shape를 반환합니다(현재 shape가 상속받은 레이아웃 및/또는 마스터 슬라이드의 shape).<br/>            현재 shape가 상속되지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides/audioframe/get_visual_bounds/#) | 렌더링된 콘텐츠를 기반으로 계산된 shape의 시각적 경계를 가져옵니다. |
| [`get_geometry_paths(self)`](/slides/python-net/ko/aspose.slides/audioframe/get_geometry_paths/#) | 기하학적 shape의 경로 복사본을 반환합니다. 좌표는 shape의 왼쪽 상단 모서리를 기준으로 합니다. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ko/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 객체에서 shape 기하학을 업데이트합니다. 좌표는 shape의 왼쪽<br/>             상단 모서리를 기준으로 해야 합니다.<br/>             shape 유형([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)로 변경합니다. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ko/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 배열에서 shape 기하학을 업데이트합니다. 좌표는 shape의 왼쪽<br/>             상단 모서리를 기준으로 해야 합니다.<br/>             shape 유형([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)로 변경합니다. |
| [`create_shape_elements(self)`](/slides/python-net/ko/aspose.slides/audioframe/create_shape_elements/#) | shape 요소들의 배열을 생성하고 반환합니다. |

### 참조
* 클래스 [`AudioFrame`](/slides/python-net/ko/aspose.slides/audioframe)
* 클래스 [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape)
* 클래스 [`PictureFrame`](/slides/python-net/ko/aspose.slides/pictureframe)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)