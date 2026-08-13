---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 HTML 문자열에서 텍스트를 컬렉션에 추가합니다.
type: docs
weight: 157
url: /ko/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) 메서드

지정된 HTML 문자열에서 텍스트를 컬렉션에 추가합니다.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 텍스트. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 메서드

지정된 HTML 문자열에서 텍스트를 컬렉션에 추가합니다.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 텍스트. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | URI를 해석하고 참조된 객체를 가져오는 콜백 객체. |
| uri | [System::String](../../../system/string/) | HTML 문서를 추가하기 위한 URI. 상대 링크 해석에 사용됩니다. |

## 비고

해결자를 지정하면 잠재적인 취약점이 발생할 수 있습니다. 주의해서 사용하십시오.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [ParagraphCollection](../)
* 클래스 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)