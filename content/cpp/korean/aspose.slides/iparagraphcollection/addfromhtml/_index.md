---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 HTML 문자열에서 텍스트를 컬렉션에 추가합니다.
type: docs
weight: 92
url: /ko/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) 메서드


지정된 HTML 문자열에서 텍스트를 컬렉션에 추가합니다.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 텍스트. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 메서드


지정된 HTML 문자열에서 텍스트를 컬렉션에 추가합니다.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 텍스트. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | URI를 해결하고 참조된 객체를 가져오는 리졸버 콜백 객체. |
| uri | [System::String](../../../system/string/) | HTML 문서를 추가하기 위한 URI. 상대 링크를 해결하는 데 사용됩니다. |
## 비고



리졸버를 지정하면 잠재적인 취약점이 발생할 수 있습니다. 주의해서 사용하십시오.
## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IParagraphCollection](../)
* 클래스 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)