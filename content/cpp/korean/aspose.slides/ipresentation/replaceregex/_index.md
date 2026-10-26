---
title: ReplaceRegex()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 정규식과 일치하는 모든 항목을 지정된 문자열로 교체합니다.
type: docs
weight: 495
url: /ko/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) 메서드

정규식과 일치하는 모든 항목을 지정된 문자열로 교체합니다.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 교체할 문자열을 가져오기 위한 정규식 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/). |
| newText | [System::String](../../../system/string/) | 교체될 문자열의 모든 발생을 대체하는 문자열. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 검색 결과 [IFindResultCallback](../../ifindresultcallback/)를 수신하기 위한 콜백 객체. |
## 비고

다음 코드 샘플은 지정된 문자열을 사용하여 정규식으로 텍스트를 교체하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Regex](../../../system.text.regularexpressions/regex/)
* 클래스 [String](../../../system/string/)
* 클래스 [IFindResultCallback](../../ifindresultcallback/)
* 클래스 [IPresentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)