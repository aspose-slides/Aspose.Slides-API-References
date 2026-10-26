---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API 레퍼런스
description: HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.
type: docs
weight: 144
url: /ko/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오기 위해 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI입니다. 상대 링크를 확인하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## ISlideCollection::AddFromHtml(System::String) method


HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |

### 반환값

추가된 슬라이드

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML 파일의 소스로 사용될 TextReader 객체. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오기 위해 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI입니다. 상대 링크를 확인하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method


HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML 파일의 소스로 사용될 TextReader 객체. |

### 반환값

추가된 슬라이드

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오기 위해 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI입니다. 상대 링크를 확인하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method


HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체. |

### 반환값

추가된 슬라이드

## 또한 보기

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [ISlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)