---
title: ReplaceText()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다.
type: docs
weight: 521
url: /ko/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 메서드

지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다.

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | 교체될 문자열. |
| newText | [System::String](../../../system/string/) | oldText의 모든 발생을 교체할 문자열. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 텍스트 검색 옵션 [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 검색 결과를 받기 위한 콜백 객체 [IFindResultCallback](../../ifindresultcallback/). |

## 비고

다음 샘플 코드는 하나의 지정된 문자열을 다른 지정된 문자열로 교체하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 모든 개별 'the' 발생을 '<em><strong>'으로 교체합니다.
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)