---
title: InsertFromHtml()
second_title: Aspose.Slides for C++ API 參考
description: 從 HTML 文字建立投影片，並在指定位置插入至集合中。
type: docs
weight: 157
url: /zh-hant/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要加入的 HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |

### 回傳值

已新增投影片。

## ISlideCollection::InsertFromHtml(int32_t, System::String) 方法

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要加入的 HTML。 |

### 回傳值

已新增投影片

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 將用作 HTML 檔案來源的 TextReader 物件。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |

### 回傳值

已新增投影片。

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) 方法

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 將用作 HTML 檔案來源的 TextReader 物件。 |

### 回傳值

已新增投影片

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 將用作 HTML 檔案來源的 Stream 物件。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |

### 回傳值

已新增投影片。

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) 方法

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 將用作 HTML 檔案來源的 Stream 物件。 |

### 回傳值

已新增投影片

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) 方法

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要加入的 HTML。 |
| useSlideWithIndexAsStart | **bool** | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若 **true**，則資料插入會從具有指定索引的投影片上的空白處開始。若 **false**，則資料會加入已建立的投影片中。 |

### 回傳值

已新增投影片

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) 方法

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要加入的 HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |
| useSlideWithIndexAsStart | **bool** | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若 **true**，則資料插入會從具有指定索引的投影片上的空白處開始。若 **false**，則資料會加入已建立的投影片中。 |

### 回傳值

已新增投影片。

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) 方法

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 將用作 HTML 檔案來源的 Stream 物件。 |
| useSlideWithIndexAsStart | **bool** | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若 **true**，則資料插入會從具有指定索引的投影片上的空白處開始。若 **false**，則資料會加入已建立的投影片中。 |

### 回傳值

已新增投影片

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) 方法

從 HTML 文字建立投影片，並在指定位置插入至集合中。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 將用作 HTML 檔案來源的 Stream 物件。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |
| useSlideWithIndexAsStart | **bool** | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若 **true**，則資料插入會從具有指定索引的投影片上的空白處開始。若 **false**，則資料會加入已建立的投影片中。 |

### 回傳值

已新增投影片。

## 參見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlide](../../islide/)
* 類別 [String](../../../system/string/)
* 類別 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 類別 [ISlideCollection](../)
* 類別 [TextReader](../../../system.io/textreader/)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)