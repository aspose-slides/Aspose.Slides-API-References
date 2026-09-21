---
title: TextFrame class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/textframe/
---
## TextFrame 클래스

TextFrame을 나타냅니다.

TextFrame 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`paragraphs`](/slides/python-net/ko/aspose.slides/textframe/paragraphs/) | 프레임에 있는 모든 단락의 목록을 반환합니다.<br/>            읽기 전용 [`IParagraphCollection`](/slides/python-net/ko/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ko/aspose.slides/textframe/text/) | TextFrame의 일반 텍스트를 가져오거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`text_frame_format`](/slides/python-net/ko/aspose.slides/textframe/text_frame_format/) | 이 TextFrame 객체의 서식 개체를 반환합니다.<br/>            읽기 전용 [`ITextFrameFormat`](/slides/python-net/ko/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/textframe/hyperlink_queries/) | 포함된 하이퍼링크에 대한 쉬운 액세스를 제공합니다.<br/>            읽기 전용 [`IHyperlinkQueries`](/slides/python-net/ko/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/ko/aspose.slides/textframe/slide/) | TextFrame의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/textframe/presentation/) | TextFrame의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/ko/aspose.slides/textframe/parent_shape/) | 상위 객체가 IShape 인터페이스를 구현하지 않을 경우 상위 도형 또는 None을 반환합니다<br/>            읽기 전용 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ko/aspose.slides/textframe/parent_cell/) | 상위 객체가 ICell 인터페이스를 구현하지 않을 경우 상위 셀 또는 None을 반환합니다.<br/>            읽기 전용 [`ICell`](/slides/python-net/ko/aspose.slides/icell). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ko/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | 지정된 색상으로 샘플 텍스트의 모든 일치를 강조 표시합니다. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ko/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | 지정된 색상으로 샘플 텍스트의 모든 일치를 강조 표시합니다. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ko/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | 지정된 색상으로 샘플 텍스트의 모든 일치를 강조 표시합니다. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ko/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | 지정된 색상으로 정규식의 모든 일치를 강조 표시합니다. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ko/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | 지정된 색상으로 정규식의 모든 일치를 강조 표시합니다. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/textframe/join_portions_with_same_formatting/#) | 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| [`split_text_by_columns(self)`](/slides/python-net/ko/aspose.slides/textframe/split_text_by_columns/#) | [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe)의 텍스트 내용을 문자열 배열로 분할합니다,<br/>            각 요소는 프레임 내의 별도 텍스트 열에 해당합니다. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ko/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ko/aspose.slides/textframe/replace_regex/#str-str) | 정규식의 모든 일치를 지정된 문자열로 교체합니다. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)