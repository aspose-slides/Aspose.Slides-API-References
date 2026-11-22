---
title: ITextFrame class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/itextframe/
---
## ITextFrame 클래스

TextFrame을 나타냅니다.

ITextFrame 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/ko/aspose.slides/itextframe/paragraphs/) | 프레임의 모든 단락 목록을 반환합니다.<br/>            읽기 전용 [`IParagraphCollection`](/slides/python-net/ko/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ko/aspose.slides/itextframe/text/) | TextFrame의 일반 텍스트를 가져오거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`text_frame_format`](/slides/python-net/ko/aspose.slides/itextframe/text_frame_format/) | 이 TextFrame 객체의 서식 개체를 반환합니다.<br/>            읽기 전용 [`ITextFrameFormat`](/slides/python-net/ko/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/itextframe/hyperlink_queries/) | 포함된 하이퍼링크에 대한 쉬운 접근을 제공합니다.<br/>            읽기 전용 [`IHyperlinkQueries`](/slides/python-net/ko/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/ko/aspose.slides/itextframe/parent_shape/) | 부모 도형을 반환하거나, 부모 객체가 IShape 인터페이스를 구현하지 않으면 None을 반환합니다<br/>            읽기 전용 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ko/aspose.slides/itextframe/parent_cell/) | 부모 셀을 반환하거나, 부모 객체가 ICell 인터페이스를 구현하지 않으면 None을 반환합니다.<br/>            읽기 전용 [`ICell`](/slides/python-net/ko/aspose.slides/icell). |
| [`slide`](/slides/python-net/ko/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/itextframe/presentation/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ko/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | 지정된 색상으로 샘플 텍스트의 모든 일치를 강조 표시합니다. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ko/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | 지정된 색상으로 샘플 텍스트의 모든 일치를 강조 표시합니다. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ko/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | 지정된 색상으로 샘플 텍스트의 모든 일치를 강조 표시합니다. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ko/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | 지정된 색상으로 정규식의 모든 일치를 강조 표시합니다. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ko/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | 지정된 색상으로 정규식의 모든 일치를 강조 표시합니다. |
| [`get_text_rect(self)`](/slides/python-net/ko/aspose.slides/itextframe/get_text_rect/#) | 부모 도형의 기하학에 의해 정의된 텍스트 사각형을 가져옵니다. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/itextframe/join_portions_with_same_formatting/#) | 모든 단락에서 동일한 서식을 가진 런을 결합합니다. |
| [`split_text_by_columns(self)`](/slides/python-net/ko/aspose.slides/itextframe/split_text_by_columns/#) | [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe)의 텍스트 내용을 문자열 배열로 분할합니다, <br/>            각 요소는 프레임 내 별도의 텍스트 열에 해당합니다. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ko/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ko/aspose.slides/itextframe/replace_regex/#str-str) | 정규식의 모든 일치를 지정된 문자열로 교체합니다. |

### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)