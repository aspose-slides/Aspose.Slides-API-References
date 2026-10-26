---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API 레퍼런스
description: HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.
type: docs
weight: 196
url: /ko/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 메서드


HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## SlideCollection::AddFromHtml(System::String) 메서드


HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |

### 반환값

추가된 슬라이드

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 메서드


HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML 파일의 소스로 사용될 TextReader 객체입니다. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) 메서드


HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML 파일의 소스로 사용될 TextReader 객체입니다. |

### 반환값

추가된 슬라이드

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 메서드


HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체입니다. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) 메서드


HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체입니다. |

### 반환값

추가된 슬라이드
## 비고




```cpp
// Presentation 클래스의 인스턴스를 생성합니다.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // AddFromHtml 메서드를 호출하고 HTML 파일을 전달합니다.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Save 메서드를 사용하여 파일을 PowerPoint 문서로 저장합니다.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlide](../../islide/)
* 클래스 [String](../../../system/string/)
* 클래스 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 클래스 [SlideCollection](../)
* 클래스 [TextReader](../../../system.io/textreader/)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)