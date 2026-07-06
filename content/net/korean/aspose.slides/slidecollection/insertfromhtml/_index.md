---
title: InsertFromHtml
second_title: Aspose.Sildes for .NET API 레퍼런스
description: HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.
type: docs
weight: 140
url: /ko/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 삽입할 위치. |
| htmlText | String | 추가할 HTML. |
| resolver | IExternalResourceResolver | 외부 객체를 가져오는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | String | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

### 참조

* 인터페이스 [ISlide](../../islide)
* 인터페이스 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 클래스 [SlideCollection](../../slidecollection)
* 네임스페이스 [Aspose.Slides](../../slidecollection)
* 어셈블리 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 삽입할 위치. |
| htmlText | String | 추가할 HTML. |
| resolver | IExternalResourceResolver | 외부 객체를 가져오는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | String | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |
| useSlideWithIndexAsStart | Boolean | 이 플래그는 삽입을 시작하는 방법을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**이면 데이터 삽입이 지정된 인덱스의 슬라이드의 빈 공간에서 시작됩니다. **false**이면 데이터가 생성된 슬라이드에 추가됩니다. |

### 반환값

추가된 슬라이드.

### 참조

* 인터페이스 [ISlide](../../islide)
* 인터페이스 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 클래스 [SlideCollection](../../slidecollection)
* 네임스페이스 [Aspose.Slides](../../slidecollection)
* 어셈블리 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 삽입할 위치. |
| htmlText | String | 추가할 HTML. |

### 반환값

추가된 슬라이드

### 참조

* 인터페이스 [ISlide](../../islide)
* 클래스 [SlideCollection](../../slidecollection)
* 네임스페이스 [Aspose.Slides](../../slidecollection)
* 어셈블리 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 삽입할 위치. |
| htmlText | String | 추가할 HTML. |
| useSlideWithIndexAsStart | Boolean | 이 플래그는 삽입을 시작하는 방법을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**이면 데이터 삽입이 지정된 인덱스의 슬라이드의 빈 공간에서 시작됩니다. **false**이면 데이터가 생성된 슬라이드에 추가됩니다. |

### 반환값

추가된 슬라이드

### 참조

* 인터페이스 [ISlide](../../islide)
* 클래스 [SlideCollection](../../slidecollection)
* 네임스페이스 [Aspose.Slides](../../slidecollection)
* 어셈블리 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 삽입할 위치. |
| htmlReader | TextReader | HTML 파일의 소스로 사용될 TextReader 객체. |
| resolver | IExternalResourceResolver | 외부 객체를 가져오는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | String | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

### 참조

* 인터페이스 [ISlide](../../islide)
* 인터페이스 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 클래스 [SlideCollection](../../slidecollection)
* 네임스페이스 [Aspose.Slides](../../slidecollection)
* 어셈블리 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 삽입할 위치. |
| htmlReader | TextReader | HTML 파일의 소스로 사용될 TextReader 객체. |

### 반환값

추가된 슬라이드

### 참조

* 인터페이스 [ISlide](../../islide)
* 클래스 [SlideCollection](../../slidecollection)
* 네임스페이스 [Aspose.Slides](../../slidecollection)
* 어셈블리 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 삽입할 위치. |
| htmlStream | Stream | HTML 파일의 소스로 사용될 Stream 객체. |
| resolver | IExternalResourceResolver | 외부 객체를 가져오는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | String | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### 반환값

추가된 슬라이드.

### 참조

* 인터페이스 [ISlide](../../islide)
* 인터페이스 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 클래스 [SlideCollection](../../slidecollection)
* 네임스페이스 [Aspose.Slides](../../slidecollection)
* 어셈블리 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 삽입할 위치. |
| htmlStream | Stream | HTML 파일의 소스로 사용될 Stream 객체. |
| resolver | IExternalResourceResolver | 외부 객체를 가져오는 콜백 객체. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| uri | String | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |
| useSlideWithIndexAsStart | Boolean | 이 플래그는 삽입을 시작하는 방법을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**이면 데이터 삽입이 지정된 인덱스의 슬라이드의 빈 공간에서 시작됩니다. **false**이면 데이터가 생성된 슬라이드에 추가됩니다. |

### 반환값

추가된 슬라이드.

### 참조

* 인터페이스 [ISlide](../../islide)
* 인터페이스 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 클래스 [SlideCollection](../../slidecollection)
* 네임스페이스 [Aspose.Slides](../../slidecollection)
* 어셈블리 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 삽입할 위치. |
| htmlStream | Stream | HTML 파일의 소스로 사용될 Stream 객체. |

### 반환값

추가된 슬라이드

### 참조

* 인터페이스 [ISlide](../../islide)
* 클래스 [SlideCollection](../../slidecollection)
* 네임스페이스 [Aspose.Slides](../../slidecollection)
* 어셈블리 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 삽입할 위치. |
| htmlStream | Stream | HTML 파일의 소스로 사용될 Stream 객체. |
| useSlideWithIndexAsStart | Boolean | 이 플래그는 삽입을 시작하는 방법을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다. **true**이면 데이터 삽입이 지정된 인덱스의 슬라이드의 빈 공간에서 시작됩니다. **false**이면 데이터가 생성된 슬라이드에 추가됩니다. |

### 반환값

추가된 슬라이드

### 참조

* 인터페이스 [ISlide](../../islide)
* 클래스 [SlideCollection](../../slidecollection)
* 네임스페이스 [Aspose.Slides](../../slidecollection)
* 어셈블리 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->