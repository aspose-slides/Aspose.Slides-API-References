---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API Reference
description: Creates slides from HTML text and adds them to the end of the collection.
type: docs
weight: 196
url: /cpp/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Creates slides from HTML text and adds them to the end of the collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html to add. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Return Value

Added slides.

## SlideCollection::AddFromHtml(System::String) method


Creates slides from HTML text and adds them to the end of the collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html to add. |

### Return Value

Added slides

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Creates slides from HTML text and adds them to the end of the collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader object which will be used as a source of a HTML file. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Return Value

Added slides.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method


Creates slides from HTML text and adds them to the end of the collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader object which will be used as a source of a HTML file. |

### Return Value

Added slides

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Creates slides from HTML text and adds them to the end of the collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Return Value

Added slides.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method


Creates slides from HTML text and adds them to the end of the collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |

### Return Value

Added slides
## Remarks




```cpp
// Create an instance of the Presentation class.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Call the AddFromHtml method and pass the HTML file.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Use the Save method to save the file as a PowerPoint document.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## See Also

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