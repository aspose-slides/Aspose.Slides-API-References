---
title: InsertFromHtml()
second_title: Aspose.Slides for C++ API 레퍼런스
description: HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.
type: docs
weight: 157
url: /ko/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI. 상대 링크를 해석하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## ISlideCollection::InsertFromHtml(int32_t, System::String) method

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |

### 반환값

추가된 슬라이드

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML 파일의 소스로 사용될 TextReader 객체. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI. 상대 링크를 해석하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML 파일의 소스로 사용될 TextReader 객체. |

### 반환값

추가된 슬라이드

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI. 상대 링크를 해석하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체. |

### 반환값

추가된 슬라이드

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) method

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |
| useSlideWithIndexAsStart | **bool** | 삽입을 시작할 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**이면 지정된 인덱스 슬라이드의 빈 공간에서 데이터 삽입이 시작됩니다. **false**이면 생성된 슬라이드에 데이터가 추가됩니다. |

### 반환값

추가된 슬라이드

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI. 상대 링크를 해석하는 데 사용됩니다. |
| useSlideWithIndexAsStart | **bool** | 삽입을 시작할 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**이면 지정된 인덱스 슬라이드의 빈 공간에서 데이터 삽입이 시작됩니다. **false**이면 생성된 슬라이드에 데이터가 추가됩니다. |

### 반환값

추가된 슬라이드.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체. |
| useSlideWithIndexAsStart | **bool** | 삽입을 시작할 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**이면 지정된 인덱스 슬라이드의 빈 공간에서 데이터 삽입이 시작됩니다. **false**이면 생성된 슬라이드에 데이터가 추가됩니다. |

### 반환값

추가된 슬라이드

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI. 상대 링크를 해석하는 데 사용됩니다. |
| useSlideWithIndexAsStart | **bool** | 삽입을 시작할 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**이면 지정된 인덱스 슬라이드의 빈 공간에서 데이터 삽입이 시작됩니다. **false**이면 생성된 슬라이드에 데이터가 추가됩니다. |

### 반환값

추가된 슬라이드.

## 또 보기

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlide](../../islide/)
* 클래스 [String](../../../system/string/)
* 클래스 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 클래스 [ISlideCollection](../)
* 클래스 [TextReader](../../../system.io/textreader/)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)