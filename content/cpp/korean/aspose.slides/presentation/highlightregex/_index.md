---
title: HighlightRegex()
second_title: Aspose.Slides C++ API 참조
description: 지정된 색상으로 정규식의 모든 일치를 강조 표시합니다.
type: docs
weight: 508
url: /ko/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) 메서드

지정된 색상으로 정규식의 모든 일치를 강조 표시합니다.

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 강조 표시할 문자열을 얻기 위한 정규식 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/). |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조 표시할 색상. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 검색 결과 [IFindResultCallback](../../ifindresultcallback/)를 수신하기 위한 콜백 객체. |

## 비고

다음 코드 예제는 정규식을 사용하여 PowerPoint [Presentation](../)에서 텍스트를 강조 표시하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Regex](../../../system.text.regularexpressions/regex/)
* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [IFindResultCallback](../../ifindresultcallback/)
* 클래스 [Presentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)