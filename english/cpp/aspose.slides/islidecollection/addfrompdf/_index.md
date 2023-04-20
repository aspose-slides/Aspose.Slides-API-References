---
title: AddFromPdf()
second_title: Aspose.Slides for C++ API Reference
description: Creates slides from the PDF document and adds them to the end of the collection.
type: docs
weight: 131
url: /cpp/aspose.slides/islidecollection/addfrompdf/
---
## ISlideCollection::AddFromPdf(System::String) method


Creates slides from the PDF document and adds them to the end of the collection.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | A path to the PDF document |

### Return Value

Added slides
## Remarks



Example: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) method


Creates slides from the PDF document and adds them to the end of the collection.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A stream which will be used as a source of the PDF document |

### Return Value

Added slides
## Remarks



Example: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [ISlideCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)