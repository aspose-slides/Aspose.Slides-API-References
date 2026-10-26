---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController 클래스

WOFF 형식으로 모든 프레젠테이션 글꼴을 포함하기 위해 사용하는 포맷팅 컨트롤러 클래스입니다.

EmbedAllFontsHtmlController 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | 새로운 인스턴스를 생성합니다 |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | 새로운 인스턴스를 생성합니다 |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | HTML 문서 헤더를 작성하기 위해 호출됩니다. 프레젠테이션 변환당 한 번 호출됩니다. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | HTML 문서 푸터를 작성하기 위해 호출됩니다. 프레젠테이션 변환당 한 번 호출됩니다. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | HTML 슬라이드 헤더를 작성하기 위해 호출됩니다. 각 슬라이드마다 한 번 호출됩니다. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | HTML 슬라이드 푸터를 작성하기 위해 호출됩니다. 각 슬라이드마다 한 번 호출됩니다. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | 도형 렌더링 전에 호출됩니다. 각 도형마다 한 번 호출됩니다. 이 함수가 generator에 무언가를 쓰면 현재 슬라이드 이미지 생성이 완료되고, 추가된 HTML 조각이 삽입되며, 새로운 이미지가 이전 이미지 위에서 시작됩니다. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | 도형 렌더링 전에 호출됩니다. 각 도형마다 한 번 호출됩니다. 이 함수가 generator에 무언가를 쓰면 현재 슬라이드 이미지 생성이 완료되고, 추가된 HTML 조각이 삽입되며, 새로운 이미지가 이전 이미지 위에서 시작됩니다. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)에 포함된 모든 글꼴을 씁니다. |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | 데이터를 base64 형식으로 HTML 문서 자체에 씁니다. |


### 참고
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)