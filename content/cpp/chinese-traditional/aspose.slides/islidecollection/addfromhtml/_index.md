---
title: AddFromHtml()
second_title: Aspose.Slides C++ API 參考文件
description: 從 HTML 文字建立投影片，並將它們新增至集合的末端。
type: docs
weight: 144
url: /zh-hant/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

從 HTML 文字建立投影片，並將它們新增到集合的末端。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 要新增的 Html。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，將會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |

### 回傳值

已新增的投影片。

## ISlideCollection::AddFromHtml(System::String) 方法

從 HTML 文字建立投影片，並將它們新增到集合的末端。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 要新增的 Html。 |

### 回傳值

已新增的投影片

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

從 HTML 文字建立投影片，並將它們新增到集合的末端。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 用作 HTML 檔案來源的 TextReader 物件。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，將會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |

### 回傳值

已新增的投影片。

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) 方法

從 HTML 文字建立投影片，並將它們新增到集合的末端。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 用作 HTML 檔案來源的 TextReader 物件。 |

### 回傳值

已新增的投影片

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

從 HTML 文字建立投影片，並將它們新增到集合的末端。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用作 HTML 檔案來源的 Stream 物件。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，將會忽略所有外部物件。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用於解析相對連結。 |

### 回傳值

已新增的投影片。

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) 方法

從 HTML 文字建立投影片，並將它們新增到集合的末端。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用作 HTML 檔案來源的 Stream 物件。 |

### 回傳值

已新增的投影片

## 另請參閱

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