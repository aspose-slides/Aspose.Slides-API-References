---
title: InsertFromHtml()
second_title: Aspose.Slides for C++ API 參考手冊
description: 從 HTML 文字建立投影片，並在指定位置將其插入至集合中。
type: docs
weight: 209
url: /zh-hant/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要加入的 HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |

### 返回值

已加入的投影片。

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要加入的 HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |
| useSlideWithIndexAsStart | **bool** | 此旗標決定插入的起始方式：從新投影片或從指定索引的投影片開始。如果為 **true**，則資料插入會從指定索引投影片的空白處開始；若為 **false**，則資料會加入已建立的投影片。 |

### 返回值

已加入的投影片。

## SlideCollection::InsertFromHtml(int32_t, System::String) method

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要加入的 HTML。 |

### 返回值

已加入的投影片

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) method

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要加入的 HTML。 |
| useSlideWithIndexAsStart | **bool** | 此旗標決定插入的起始方式：從新投影片或從指定索引的投影片開始。如果為 **true**，則資料插入會從指定索引投影片的空白處開始；若為 **false**，則資料會加入已建立的投影片。 |

### 返回值

已加入的投影片

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 用作 HTML 檔案來源的 TextReader 物件。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |

### 返回值

已加入的投影片。

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 用作 HTML 檔案來源的 TextReader 物件。 |

### 返回值

已加入的投影片

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用作 HTML 檔案來源的 Stream 物件。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |

### 返回值

已加入的投影片。

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用作 HTML 檔案來源的 Stream 物件。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |
| useSlideWithIndexAsStart | **bool** | 此旗標決定插入的起始方式：從新投影片或從指定索引的投影片開始。如果為 **true**，則資料插入會從指定索引投影片的空白處開始；若為 **false**，則資料會加入已建立的投影片。 |

### 返回值

已加入的投影片。

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用作 HTML 檔案來源的 Stream 物件。 |

### 返回值

已加入的投影片

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用作 HTML 檔案來源的 Stream 物件。 |
| useSlideWithIndexAsStart | **bool** | 此旗標決定插入的起始方式：從新投影片或從指定索引的投影片開始。如果為 **true**，則資料插入會從指定索引投影片的空白處開始；若為 **false**，則資料會加入已建立的投影片。 |

### 返回值

已加入的投影片

## 另請參閱

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