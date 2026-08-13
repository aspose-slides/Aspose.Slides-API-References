---
title: InsertFromHtml()
second_title: C++용 Aspose.Slides API 레퍼런스
description: HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.
type: docs
weight: 209
url: /ko/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 메서드


HTML 텍스트에서 슬라이드를 만들고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입 위치. |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 null인 경우 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) 메서드


HTML 텍스트에서 슬라이드를 만들고 지정된 위치에 컬렉션에 삽입합니다.
```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입 위치. |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |
| useSlideWithIndexAsStart | **bool** | 이 플래그는 삽입을 시작하는 방식을 결정합니다: 새 슬라이드에서 시작할지 지정된 인덱스의 슬라이드에서 시작할지. **true**인 경우, 데이터 삽입은 지정된 인덱스 슬라이드의 빈 공간에서 시작됩니다. **false**인 경우, 데이터는 생성된 슬라이드에 추가됩니다. |

### 반환 값

추가된 슬라이드.

## SlideCollection::InsertFromHtml(int32_t, System::String) 메서드

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```

### 인수
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입 위치. |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |

### 반환값

추가된 슬라이드

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) 메서드

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입 위치. |
| htmlText | [System::String](../../../system/string/) | 추가할 HTML. |
| useSlideWithIndexAsStart | **bool** | 이 플래그는 삽입을 시작하는 방법을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**인 경우, 데이터 삽입은 지정된 인덱스의 슬라이드의 빈 공간에서 시작됩니다. **false**인 경우, 데이터는 생성된 슬라이드에 추가됩니다. |

### 반환값

추가된 슬라이드

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 메서드

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입 위치. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML 파일의 소스로 사용되는 TextReader 객체. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) 메서드

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.
```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML 파일의 소스로 사용될 TextReader 객체. |

### 반환값

추가된 슬라이드

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 메서드

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) 메서드

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | [System::String](../../../system/string/) | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |
| useSlideWithIndexAsStart | **bool** | 이 플래그는 삽입을 시작하는 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**인 경우 데이터 삽입이 지정된 인덱스 슬라이드의 빈 공간에서 시작됩니다. **false**인 경우 데이터가 생성된 슬라이드에 추가됩니다. |

### 반환값

추가된 슬라이드.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) 메서드

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체. |

### 반환값

추가된 슬라이드

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) 메서드

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 위치. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML 파일의 소스로 사용될 Stream 객체. |
| useSlideWithIndexAsStart | **bool** | 이 플래그는 삽입을 시작하는 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**인 경우 데이터 삽입이 지정된 인덱스 슬라이드의 빈 공간에서 시작됩니다. **false**인 경우 데이터가 생성된 슬라이드에 추가됩니다. |

### 반환값

추가된 슬라이드

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [SlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)