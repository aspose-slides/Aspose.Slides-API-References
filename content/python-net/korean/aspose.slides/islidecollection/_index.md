---
title: ISlideCollection class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/islidecollection/
---
## ISlideCollection 클래스

슬라이드 컬렉션을 나타냅니다.

ISlideCollection 형식은 다음 멤버를 노출합니다:

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [`ISlide`](/slides/python-net/ko/aspose.slides/islide).

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides/islidecollection/__getitem__/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/ko/aspose.slides/islidecollection/add_clone/#islide) | 지정된 슬라이드의 복사본을 컬렉션 끝에 추가합니다. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/ko/aspose.slides/islidecollection/add_clone/#islide-isection) | 지정된 슬라이드의 복사본을 지정된 섹션 끝에 추가합니다. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/ko/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | 지정된 슬라이드의 복사본을 컬렉션 끝에 추가합니다. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ko/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | 지정된 원본 슬라이드의 복사본을 컬렉션 끝에 추가합니다.<br/>            적절한 레이아웃은 지정된 마스터에서 자동으로 선택됩니다.<br/>            (적절한 레이아웃은 원본 슬라이드의 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃입니다.) 적절한 레이아웃이 없으면<br/>            원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout이 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout이 false인 경우). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_clone/#int-islide) | 지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | 지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | 지정된 원본 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.<br/>            적절한 레이아웃은 지정된 마스터에서 자동으로 선택됩니다.<br/>            (적절한 레이아웃은 원본 슬라이드의 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃입니다.) 적절한 레이아웃이 없으면<br/>            원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout이 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout이 false인 경우). |
| [`to_array(self)`](/slides/python-net/ko/aspose.slides/islidecollection/to_array/#) | 모든 슬라이드를 포함하는 배열을 생성하고 반환합니다. |
| [`to_array(self, start_index, count)`](/slides/python-net/ko/aspose.slides/islidecollection/to_array/#int-int) | 지정된 범위의 모든 슬라이드를 포함하는 배열을 생성하고 반환합니다. |
| [`reorder(self, index, slide)`](/slides/python-net/ko/aspose.slides/islidecollection/reorder/#int-islide) | 컬렉션에서 슬라이드를 지정된 위치로 이동합니다. |
| [`reorder(self, index, slides)`](/slides/python-net/ko/aspose.slides/islidecollection/reorder/#int-listislide) | 컬렉션에서 슬라이드를 지정된 위치로 이동합니다.<br/>            슬라이드는 리스트에 나타나는 순서대로 인덱스부터 배치됩니다. |
| [`add_from_pdf(self, path)`](/slides/python-net/ko/aspose.slides/islidecollection/add_from_pdf/#str) | PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/ko/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | PDF 문서에서 슬라이드를 생성하고 PDF 가져오기 옵션을 고려하여 컬렉션 끝에 추가합니다. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/ko/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/ko/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/ko/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [`add_from_html(self, html_text)`](/slides/python-net/ko/aspose.slides/islidecollection/add_from_html/#str) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/ko/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [`add_from_html(self, html_stream)`](/slides/python-net/ko/aspose.slides/islidecollection/add_from_html/#iorawiobase) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_from_html/#int-str) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [`add_empty_slide(self, layout)`](/slides/python-net/ko/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | 새 빈 슬라이드를 컬렉션 끝에 추가합니다. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/ko/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | 지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [`remove(self, value)`](/slides/python-net/ko/aspose.slides/islidecollection/remove/#islide) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides/islidecollection/remove_at/#int) | 컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다. |
| [`index_of(self, slide)`](/slides/python-net/ko/aspose.slides/islidecollection/index_of/#islide) | 컬렉션에서 지정된 슬라이드의 인덱스를 반환합니다. |

### 참조
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)