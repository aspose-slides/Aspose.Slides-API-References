---
title: ReplaceRegex()
second_title: Aspose.Slides C++용 API 참조
description: 정규 표현식과 일치하는 모든 항목을 지정된 문자열로 교체합니다.
type: docs
weight: 534
url: /ko/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) 메서드


정규 표현식과 일치하는 모든 항목을 지정된 문자열로 교체합니다.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 대체할 문자열을 얻기 위한 정규 표현식 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/). |
| newText | [System::String](../../../system/string/) | 대체할 문자열들의 모든 발생을 교체하는 문자열. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 검색 결과 [IFindResultCallback](../../ifindresultcallback/)를 수신하기 위한 콜백 객체. |
## 비고



다음 코드 예제는 정규 표현식을 사용하여 지정된 문자열로 텍스트를 교체하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// 10자 이상인 모든 단어를 '<em><strong>'로 교체합니다
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)