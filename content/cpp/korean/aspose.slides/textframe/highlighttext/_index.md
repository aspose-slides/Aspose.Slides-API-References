---
title: HighlightText()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조 표시합니다.
type: docs
weight: 131
url: /ko/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) 메서드

지정된 색상으로 샘플 텍스트와 일치하는 모든 부분을 강조 표시합니다.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 강조할 텍스트 샘플. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조할 색상. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) 메서드

지정된 색상으로 샘플 텍스트와 일치하는 모든 부분을 강조 표시합니다.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 강조할 텍스트. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조할 색상. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | 강조 옵션. |

## 비고

사용 중단됨
:   대신 HighlightText(string text, Color highlightColor, ITextSearchOptions options) 메서드를 사용하십시오. 이 메서드는 버전 24.10 출시 이후 제거될 예정입니다.

다음 샘플 코드는 [TextFrame](../)에서 텍스트를 강조하는 방법을 보여줍니다. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 메서드

지정된 색상으로 샘플 텍스트와 일치하는 모든 부분을 강조 표시합니다.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 강조할 텍스트. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조할 색상. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 텍스트 검색 옵션 [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 검색 결과 [IFindResultCallback](../../ifindresultcallback/)를 수신하기 위한 콜백 객체. |

## 비고

다음 코드 샘플은 [TextFrame](../)에서 텍스트를 강조하는 방법을 보여줍니다. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// 모든 'important' 단어를 강조
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 모든 개별 'the' 발생을 강조
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 또 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [TextFrame](../)
* 클래스 [ITextHighlightingOptions](../../itexthighlightingoptions/)
* 클래스 [ITextSearchOptions](../../itextsearchoptions/)
* 클래스 [IFindResultCallback](../../ifindresultcallback/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)