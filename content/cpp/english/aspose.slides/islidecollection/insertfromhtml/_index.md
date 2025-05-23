---
title: InsertFromHtml()
second_title: Aspose.Slides for C++ API Reference
description: Creates slides from HTML text and inserts them to the collection at the specified position.
type: docs
weight: 157
url: /aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Creates slides from HTML text and inserts them to the collection at the specified position.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position to insert. |
| htmlText | [System::String](../../../system/string/) | Html to add. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Return Value

Added slides.

## ISlideCollection::InsertFromHtml(int32_t, System::String) method


Creates slides from HTML text and inserts them to the collection at the specified position.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position to insert. |
| htmlText | [System::String](../../../system/string/) | Html to add. |

### Return Value

Added slides

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Creates slides from HTML text and inserts them to the collection at the specified position.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position to insert. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader object which will be used as a source of a HTML file. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Return Value

Added slides.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method


Creates slides from HTML text and inserts them to the collection at the specified position.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position to insert. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader object which will be used as a source of a HTML file. |

### Return Value

Added slides

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Creates slides from HTML text and inserts them to the collection at the specified position.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position to insert. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Return Value

Added slides.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method


Creates slides from HTML text and inserts them to the collection at the specified position.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position to insert. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |

### Return Value

Added slides

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) method


Creates slides from HTML text and inserts them to the collection at the specified position.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position to insert. |
| htmlText | [System::String](../../../system/string/) | Html to add. |
| useSlideWithIndexAsStart | **bool** | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

### Return Value

Added slides

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method


Creates slides from HTML text and inserts them to the collection at the specified position.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position to insert. |
| htmlText | [System::String](../../../system/string/) | Html to add. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |
| useSlideWithIndexAsStart | **bool** | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

### Return Value

Added slides.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method


Creates slides from HTML text and inserts them to the collection at the specified position.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position to insert. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |
| useSlideWithIndexAsStart | **bool** | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

### Return Value

Added slides

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method


Creates slides from HTML text and inserts them to the collection at the specified position.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position to insert. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |
| useSlideWithIndexAsStart | **bool** | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

### Return Value

Added slides.

## See Also

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