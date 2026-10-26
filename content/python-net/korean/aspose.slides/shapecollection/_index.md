---
title: ShapeCollection class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/
---
## ShapeCollection 클래스

도형 컬렉션을 나타냅니다.

ShapeCollection 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`parent_group`](/slides/python-net/ko/aspose.slides/shapecollection/parent_group/) | 도형 컬렉션에 대한 상위 그룹 도형 객체를 가져옵니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |

지정된 인덱스에 있는 요소를 가져옵니다.<br/>            읽기 전용 [`IShape`](/slides/python-net/ko/aspose.slides/ishape).

## 인덱서

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides/shapecollection/__getitem__/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | 새 차트를 만들고, 샘플 시리즈 데이터와 설정으로 초기화한 다음,<br/>            도형 컬렉션의 끝에 추가합니다. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/ko/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | 새 차트를 만들고, 샘플 시리즈 데이터와 설정으로 초기화한 다음,<br/>            도형 컬렉션의 끝에 추가합니다. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | 새 차트를 만들고, 샘플 시리즈 데이터와 설정으로 초기화한 다음,<br/>            지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | 새 차트를 만들고, 샘플 시리즈 데이터와 설정으로 초기화한 다음,<br/>            지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/ko/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | 새 Zoom 프레임을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/ko/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | 새 Zoom 프레임을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | 새 Zoom 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | 미리 정의된 이미지가 있는 새 Zoom 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/ko/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | 새 섹션 Zoom 프레임을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/ko/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | 미리 정의된 이미지가 있는 새 섹션 Zoom 프레임을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | 새 섹션 Zoom 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | 미리 정의된 이미지가 있는 새 섹션 Zoom 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/ko/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | 새 OLE 객체 프레임을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/ko/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | 새 OLE 객체 프레임을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | 새 OLE 객체 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | 새 OLE 객체 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/ko/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | 새 비디오 프레임을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/ko/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | 새 비디오 프레임을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/ko/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | 임베드된 WAV 파일이 있는 새 오디오 프레임을 만들고 도형 컬렉션의 끝에 추가합니다.<br/>            임베드된 오디오는 Presentation.Audios 컬렉션에 추가됩니다. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/ko/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | 기존 Presentation.Audios 목록의 오디오 객체를 사용하여 새 오디오 프레임을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | 임베드된 WAV 파일이 있는 새 오디오 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 임베드된 오디오는 Presentation.Audios 컬렉션에 추가됩니다. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | 기존 Presentation.Audios 목록의 오디오 객체를 사용하여 지정된 인덱스에 도형 컬렉션에 새 오디오 프레임을 삽입합니다. |
| [`to_array(self)`](/slides/python-net/ko/aspose.slides/shapecollection/to_array/#) | 모든 도형을 포함하는 배열을 생성하고 반환합니다. |
| [`to_array(self, start_index, count)`](/slides/python-net/ko/aspose.slides/shapecollection/to_array/#int-int) | 지정된 범위의 모든 도형을 포함하는 배열을 생성하고 반환합니다. |
| [`reorder(self, index, shape)`](/slides/python-net/ko/aspose.slides/shapecollection/reorder/#int-ishape) | 지정된 도형을 도형 컬렉션 내 새로운 위치로 이동합니다. |
| [`reorder(self, index, shapes)`](/slides/python-net/ko/aspose.slides/shapecollection/reorder/#int-listishape) | 지정된 도형들을 도형 컬렉션 내에서 이동시켜 주어진 인덱스부터 배치합니다. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | 기본 서식이 적용된 새 자동 도형을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ko/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | 새 자동 도형을 만들고 도형 컬렉션의 끝에 추가합니다. 옵션으로 기본 템플릿 서식으로 초기화할 수 있습니다. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | 새 자동 도형을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 기본 템플릿 서식을 적용합니다. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | 새 자동 도형을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 옵션으로 기본 템플릿 스타일로 초기화합니다. |
| [`add_group_shape(self)`](/slides/python-net/ko/aspose.slides/shapecollection/add_group_shape/#) | 새 빈 그룹 도형을 만들고 도형 컬렉션의 끝에 추가합니다.<br/>            그룹의 프레임은 추가된 모든 도형에 맞게 자동으로 조정됩니다. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | 새 그룹 도형을 만들고, 지정된 SVG 이미지를 개별 도형으로 변환한 뒤, 결과 그룹을 도형 컬렉션의 끝에 추가합니다. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | 기본 템플릿 스타일이 적용된 새 연결기 도형을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ko/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | 새 연결기 도형을 만들고 도형 컬렉션의 끝에 추가합니다. 옵션으로 기본 템플릿 스타일을 적용합니다. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | 새 연결기 도형을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 기본 템플릿 스타일을 적용합니다. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | 새 연결기 도형을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 옵션으로 기본 템플릿 스타일을 적용합니다. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | 지정된 도형의 복사본을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/ko/aspose.slides/shapecollection/add_clone/#ishape-float-float) | 지정된 도형의 복사본을 만들고 도형 컬렉션의 끝에 추가합니다.<br/>            새 도형은 `source_shape`의 너비와 높이를 유지합니다. |
| [`add_clone(self, source_shape)`](/slides/python-net/ko/aspose.slides/shapecollection/add_clone/#ishape) | 지정된 도형의 복사본을 만들고 도형 컬렉션의 끝에 추가합니다.<br/>            복제된 도형은 원본의 위치와 크기를 유지합니다. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | 지정된 도형의 복사본을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | 지정된 도형의 복사본을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다.<br/>            새 도형은 `source_shape`의 너비와 높이를 유지합니다. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_clone/#int-ishape) | 지정된 도형의 복사본을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다.<br/>            복제된 도형은 원본의 위치와 크기를 유지합니다. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/ko/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | SmartArt 다이어그램을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | 새 요약 Zoom 프레임을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | 새 요약 Zoom 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | 새 비디오 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | CD 트랙에 연결된 새 오디오 프레임을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | CD 트랙에 연결된 새 오디오 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/ko/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | 외부 오디오 파일에 연결된 새 오디오 프레임을 만들고 도형 컬렉션의 끝에 추가합니다.<br/>            |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | 외부 오디오 파일에 연결된 새 오디오 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`index_of(self, shape)`](/slides/python-net/ko/aspose.slides/shapecollection/index_of/#ishape) | 컬렉션에서 지정된 도형이 처음 나타나는 위치의 0 기반 인덱스를 반환합니다. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/ko/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | 수학 콘텐츠를 호스팅하기 위한 새 사각형 자동 도형을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`insert_group_shape(self, index)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_group_shape/#int) | 새 빈 그룹 도형을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다.<br/>            그룹의 프레임은 추가된 모든 도형에 맞게 자동으로 조정됩니다. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/ko/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | 지정된 이미지를 포함하는 새 그림 프레임을 만들고 도형 컬렉션의 끝에 추가합니다.<br/>            |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | 지정된 이미지를 포함하는 새 그림 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/ko/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | 새 테이블을 만들고 도형 컬렉션의 끝에 추가합니다. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/ko/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | 새 테이블을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides/shapecollection/remove_at/#int) | 지정된 인덱스에 있는 도형을 도형 컬렉션에서 제거합니다. |
| [`remove(self, shape)`](/slides/python-net/ko/aspose.slides/shapecollection/remove/#ishape) | 지정된 도형이 처음 나타나는 것을 도형 컬렉션에서 제거합니다. |
| [`clear(self)`](/slides/python-net/ko/aspose.slides/shapecollection/clear/#) | 도형 컬렉션의 모든 도형을 제거합니다. |

### 참조
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)