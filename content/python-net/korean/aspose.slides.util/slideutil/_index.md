---
title: SlideUtil class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.util/slideutil/
---
## SlideUtil 클래스

프레젠테이션에서 모양과 텍스트를 검색하는 데 도움이 되는 메서드를 제공합니다.

SlideUtil 유형은 다음 멤버를 노출합니다:

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/ko/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | PPTX 프레젠테이션에서 대체 텍스트로 모양을 찾습니다. |
| [`find_shape(slide, alt_text)`](/slides/python-net/ko/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | PPTX 프레젠테이션의 슬라이드에서 대체 텍스트로 모양을 찾습니다. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/ko/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | 슬라이드의 모든 모양 배치를 변경합니다. 모양을 슬라이드의 여백이나 가장자리에 맞춥니다.<br/>            또는 서로 상대적으로 정렬합니다. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/ko/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | 슬라이드에서 선택된 모양의 배치를 변경합니다. 모양을 슬라이드의 여백이나 가장자리에 맞춥니다.<br/>             또는 서로 상대적으로 정렬합니다. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/ko/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | 그룹 모양 내 모든 모양의 배치를 변경합니다. 모양을 슬라이드의 여백이나 가장자리에 맞춥니다.<br/>            또는 서로 상대적으로 정렬합니다. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/ko/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | 그룹 모양 내 선택된 모양의 배치를 변경합니다. 모양을 슬라이드의 여백이나 가장자리에 맞춥니다.<br/>            또한 서로 상대적으로 정렬합니다. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/ko/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | 지정된 슬라이드에서 주어진 자리 표시자 유형과 일치하는 모든 모양을 검색합니다. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/ko/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | 프레젠테이션에서 텍스트를 찾아 주어진 형식으로 교체합니다. |
| [`get_all_text_boxes(slide)`](/slides/python-net/ko/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | PPTX 프레젠테이션의 슬라이드에서 모든 텍스트 프레임을 반환합니다. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/ko/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | 지정된 슬라이드에서 주어진 텍스트를 포함하는 모든 텍스트 프레임을 반환합니다. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/ko/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | PPTX 프레젠테이션의 모든 텍스트 프레임을 반환합니다. |
| [`to_save_format(format)`](/slides/python-net/ko/aspose.slides.util/slideutil/to_save_format/#sourceformat) | 소스 파일 형식을 해당 [`SaveFormat`](/slides/python-net/ko/aspose.slides.export/saveformat) 로 변환합니다. |

### 참조
* 모듈 [`aspose.slides.util`](/slides/python-net/ko/aspose.slides.util)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)