---
title: HighlightText()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조 표시합니다.
type: docs
weight: 105
url: /ko/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) method

지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조 표시합니다.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 강조 표시할 텍스트입니다. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조 표시할 색상입니다. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method

지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조 표시합니다.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 강조 표시할 텍스트입니다. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조 표시할 색상입니다. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | 강조 옵션입니다. |

사용 중단
:   대신 HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) method를 사용하십시오. 이 메서드는 버전 24.10 릴리스 후 제거될 예정입니다.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method

지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조 표시합니다.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 강조 표시할 텍스트입니다. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조 표시할 색상입니다. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 텍스트 검색 옵션 [ITextSearchOptions](../../itextsearchoptions/)입니다. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 검색 결과를 수신할 콜백 객체 [IFindResultCallback](../../ifindresultcallback/)입니다. |

## 비고

다음 코드 샘플은 [TextFrame](../../textframe/)에서 텍스트를 강조 표시하는 방법을 보여줍니다. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [ITextFrame](../)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)