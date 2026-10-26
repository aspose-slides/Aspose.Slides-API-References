---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 색상으로 정규 표현식의 모든 일치를 강조 표시합니다.
type: docs
weight: 469
url: /ko/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) 메서드


지정된 색상으로 정규 표현식의 모든 일치를 강조 표시합니다.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 강조할 문자열을 가져오기 위한 정규 표현식 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/). |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조 표시할 색상. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 검색 결과 [IFindResultCallback](../../ifindresultcallback/)를 수신하기 위한 콜백 객체. |
## 비고



다음 코드 샘플은 정규 표현식을 사용하여 PowerPoint [Presentation](../../presentation/)에서 텍스트를 강조 표시하는 방법을 보여줍니다. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// 10자 이상인 모든 단어를 강조 표시
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Regex](../../../system.text.regularexpressions/regex/)
* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [IFindResultCallback](../../ifindresultcallback/)
* 클래스 [IPresentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)