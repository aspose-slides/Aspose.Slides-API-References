---
title: IHtmlGenerator class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator 클래스

HTML 생성기.

IHtmlGenerator 유형은 다음 멤버를 제공합니다:

## 속성

| Property | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/slide_image_size/) | 슬라이드 이미지 크기를 반환합니다.<br/>            읽기 전용 [`SizeF`](/slides/python-net/ko/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | 슬라이드 이미지 크기가 지정되는 단위를 반환합니다.<br/>            읽기 전용 [`SvgCoordinateUnit`](/slides/python-net/ko/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | 슬라이드 이미지 크기가 지정되는 단위의 CSS 코드를 반환합니다.<br/>            읽기 전용 **str**. |
| [`previous_slide_index`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | 이전에 렌더링된 슬라이드의 인덱스를 반환합니다. 첫 번째 슬라이드가 렌더링 중이면 -1을 반환합니다.<br/>            읽기 전용 **int**. |
| [`slide_index`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/slide_index/) | 현재 렌더링 중인 슬라이드의 인덱스를 반환합니다.<br/>            읽기 전용 **int**. |
| [`next_slide_index`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/next_slide_index/) | 현재 슬라이드가 마지막 슬라이드인 경우 -1을 반환하고, 그렇지 않으면 다음에 렌더링될 슬라이드의 인덱스를 반환합니다.<br/>            읽기 전용 **int**. |

## 메서드

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_html/#str) | 서식이 지정된 HTML 텍스트를 추가합니다. |
| [`add_html(self, html)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | 서식이 지정된 HTML 텍스트를 추가합니다. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | 서식이 지정된 HTML 텍스트를 추가합니다. |
| [`add_text(self, text)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_text/#str) | HTML 파일에 일반 텍스트를 추가하고 특수 문자를 HTML 엔터티로 변환합니다.<br/>            줄 바꿈과 공백은 교체되지 않습니다. |
| [`add_text(self, text)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | HTML 파일에 일반 텍스트를 추가하고 특수 문자를 HTML 엔터티로 변환합니다.<br/>            줄 바꿈과 공백은 교체되지 않습니다. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | HTML 파일에 일반 텍스트를 추가하고 특수 문자를 HTML 엔터티로 변환합니다.<br/>            줄 바꿈과 공백은 교체되지 않습니다. |
| [`add_attribute_value(self, value)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | 속성 값을 인용하고 HTML 파일에 추가합니다. |
| [`add_attribute_value(self, value)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | 속성 값을 인용하고 HTML 파일에 추가합니다. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | 속성 값을 인용하고 HTML 파일에 추가합니다. |


### 참조
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)