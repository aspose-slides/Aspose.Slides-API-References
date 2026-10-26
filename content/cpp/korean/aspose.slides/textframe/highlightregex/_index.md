---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API 참조
description: 정규식과 지정된 색으로 모든 일치를 강조 표시합니다.
type: docs
weight: 157
url: /ko/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method

정규식과 지정된 색으로 모든 일치를 강조 표시합니다.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | 강조 표시할 텍스트를 얻기 위한 정규식 문자열입니다. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조 표시할 색상입니다. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | 강조 옵션입니다. |

## 비고

사용 중단됨
:   Use HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) method instead. The method will be removed after release of version 24.10.

다음 코드 샘플은 정규식을 사용하여 [TextFrame](../)에서 텍스트를 강조 표시하는 방법을 보여줍니다. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// 10자 이상인 모든 단어를 강조 표시
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

정규식과 지정된 색으로 모든 일치를 강조 표시합니다.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 강조 표시할 문자열을 얻기 위한 정규식 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)입니다. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조 표시할 색상입니다. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 검색 결과를 수신하기 위한 콜백 객체 [IFindResultCallback](../../ifindresultcallback/)입니다. |

## 비고

다음 코드 샘플은 정규식을 사용하여 [TextFrame](../)에서 텍스트를 강조 표시하는 방법을 보여줍니다. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// 10자 이상인 모든 단어를 강조 표시
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [ITextHighlightingOptions](../../itexthighlightingoptions/)
* 클래스 [TextFrame](../)
* 클래스 [Regex](../../../system.text.regularexpressions/regex/)
* 클래스 [IFindResultCallback](../../ifindresultcallback/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)