---
title: IHtmlGenerator class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator 클래스

HTML 생성기.

IHtmlGenerator 타입은 다음 멤버를 제공합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`slide_image_size`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/slide_image_size/) | 슬라이드 이미지 크기를 반환합니다.<br/>읽기 전용 **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | 슬라이드 이미지 크기가 지정되는 단위를 반환합니다.<br/>읽기 전용 [`SvgCoordinateUnit`](/slides/python-net/ko/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | 슬라이드 이미지 크기가 지정되는 단위의 CSS 코드를 반환합니다.<br/>읽기 전용 **str**. |
| [`previous_slide_index`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | 이전에 렌더링된 슬라이드의 인덱스를 반환하거나 첫 번째 슬라이드가 렌더링 중이면 -1을 반환합니다.<br/>읽기 전용 **int**. |
| [`slide_index`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/slide_index/) | 현재 렌더링 중인 슬라이드의 인덱스를 반환합니다.<br/>읽기 전용 **int**. |
| [`next_slide_index`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/next_slide_index/) | 현재 슬라이드 뒤에 렌더링될 슬라이드의 인덱스를 반환하거나 현재 마지막 슬라이드를 렌더링 중이면 -1을 반환합니다.<br/>읽기 전용 **int**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_html/#str) | 형식이 지정된 HTML 텍스트를 추가합니다. |
| [`add_html(self, html)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | 형식이 지정된 HTML 텍스트를 추가합니다. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | 형식이 지정된 HTML 텍스트를 추가합니다. |
| [`add_text(self, text)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_text/#str) | 특수 문자를 HTML 엔티티로 바꾸어 일반 텍스트를 HTML 파일에 추가합니다.<br/>줄 바꿈 및 공백은 교체되지 않습니다. |
| [`add_text(self, text)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | 특수 문자를 HTML 엔티티로 바꾸어 일반 텍스트를 HTML 파일에 추가합니다.<br/>줄 바꿈 및 공백은 교체되지 않습니다. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | 특수 문자를 HTML 엔티티로 바꾸어 일반 텍스트를 HTML 파일에 추가합니다.<br/>줄 바꿈 및 공백은 교체되지 않습니다. |
| [`add_attribute_value(self, value)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | 속성 값을 따옴표로 묶어 HTML 파일에 추가합니다. |
| [`add_attribute_value(self, value)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | 속성 값을 따옴표로 묶어 HTML 파일에 추가합니다. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | 속성 값을 따옴표로 묶어 HTML 파일에 추가합니다. |

### 참조
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)