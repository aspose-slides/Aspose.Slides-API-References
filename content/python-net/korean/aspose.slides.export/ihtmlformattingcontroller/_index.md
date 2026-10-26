---
title: IHtmlFormattingController class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController 클래스

HTML 파일 생성을 제어합니다.

IHtmlFormattingController 형식은 다음 멤버를 노출합니다:

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/ko/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | HTML 문서 헤더를 작성하기 위해 호출됩니다. 프레젠테이션 변환당 한 번 호출됩니다. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/ko/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | HTML 문서 푸터를 작성하기 위해 호출됩니다. 프레젠테이션 변환당 한 번 호출됩니다. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/ko/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | HTML 슬라이드 헤더를 작성하기 위해 호출됩니다. 각 슬라이드당 한 번 호출됩니다. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/ko/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | HTML 슬라이드 푸터를 작성하기 위해 호출됩니다. 각 슬라이드당 한 번 호출됩니다. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/ko/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | shape의 렌더링 전에 호출됩니다. 각 shape당 한 번 호출됩니다. 이 함수가 generator에 무언가를 기록하면 현재 슬라이드 이미지 생성이 종료되고, 추가된 HTML 조각이 삽입되며, 새 이미지가 이전 이미지 위에 시작됩니다. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/ko/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | shape의 렌더링 전에 호출됩니다. 각 shape당 한 번 호출됩니다. 이 함수가 generator에 무언가를 기록하면 현재 슬라이드 이미지 생성이 종료되고, 추가된 HTML 조각이 삽입되며, 새 이미지가 이전 이미지 위에 시작됩니다. |

### 참조
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)