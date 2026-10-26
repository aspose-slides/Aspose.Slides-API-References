---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 정규식의 모든 일치를 지정된 색상으로 강조 표시합니다.
type: docs
weight: 131
url: /ko/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) 메서드

지정된 색상으로 정규식의 모든 일치를 강조 표시합니다.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 강조 표시할 문자열을 얻기 위한 정규식 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조 표시할 색상 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 검색 결과 [IFindResultCallback](../../ifindresultcallback/)를 받기 위한 콜백 객체 |

## 비고

다음 코드 샘플은 정규식을 사용하여 [TextFrame](../../textframe/)에서 텍스트를 강조 표시하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) 메서드

지정된 색상으로 정규식의 모든 일치를 강조 표시합니다.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | 강조 표시할 텍스트를 얻기 위한 정규식 텍스트 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조 표시할 색상 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | 강조 옵션 |

더 이상 사용되지 않음
:   대신 HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) 메서드를 사용하십시오. 이 메서드는 버전 24.10 출시 후 제거될 예정입니다.

## 또한 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Regex](../../../system.text.regularexpressions/regex/)
* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [IFindResultCallback](../../ifindresultcallback/)
* 클래스 [ITextFrame](../)
* 클래스 [String](../../../system/string/)
* 클래스 [ITextHighlightingOptions](../../itexthighlightingoptions/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)