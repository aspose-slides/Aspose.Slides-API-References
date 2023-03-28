---
title: Save()
second_title: Aspose.Slides for C++ API Reference
description: Saves all slides of a presentation to a file with the specified format.
type: docs
weight: 391
url: /cpp/aspose.slides/ipresentation/save/
---
## IPresentation::Save([System::String](../../../system/string/), [Export::SaveFormat](../../../aspose.slides.export/saveformat/)) method


Saves all slides of a presentation to a file with the specified format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Path to the created file. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |

## See Also

* Class [String](../../../system/string/)
* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentation::Save([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>, [Export::SaveFormat](../../../aspose.slides.export/saveformat/)) method


Saves all slides of a presentation to a stream in the specified format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Output stream. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentation::Save([System::String](../../../system/string/), [Export::SaveFormat](../../../aspose.slides.export/saveformat/), [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\>) method


Saves all slides of a presentation to a file with the specified format and with additional options.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Path to the created file. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Additional format options. |

## See Also

* Class [String](../../../system/string/)
* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentation::Save([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>, [Export::SaveFormat](../../../aspose.slides.export/saveformat/), [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\>) method


Saves all slides of a presentation to a stream in the specified format and with additional options.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Output stream. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Additional format options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentation::Save([System::String](../../../system/string/), [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../../aspose.slides.export/saveformat/)) method


Saves specified slides of a presentation to a file with the specified format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Path to the created file. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentation::Save([System::String](../../../system/string/), [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../../aspose.slides.export/saveformat/), [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\>) method


Saves specified slides of a presentation to a file with the specified format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Path to the created file. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Additional format options. |

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentation::Save([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>, [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../../aspose.slides.export/saveformat/)) method


Saves specified slides of a presentation to a stream in the specified format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Output stream. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentation::Save([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>, [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../../aspose.slides.export/saveformat/), [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\>) method


Saves specified slides of a presentation to a stream in the specified format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Output stream. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Additional format options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentation::Save([System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\>) method


Saves all slides of a presentation to a set of files representing XAML markup.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | The XAML format options. |
## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentation::Save([System::String](../../../system/string/), [Export::SaveFormat](../../../aspose.slides.export/saveformat/), [System::SharedPtr](../../../system/sharedptr/)\<[System::Web::HttpResponse](../../../system.web/httpresponse/)\>, **bool**) method


Sends the presentation to the client browser. This method is absent in ClientProfile versions of Aspose.Slide.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<System::Web::HttpResponse> response, bool showInline)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | The name for the presentation that will appear at the client browser. The name should not contain path. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[System::Web::HttpResponse](../../../system.web/httpresponse/)\> | Response object where to save the document. |
| showInline | **bool** | True to show an option to open the presentation inside the browser. |

## See Also

* Class [String](../../../system/string/)
* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentation::Save([System::String](../../../system/string/), [Export::SaveFormat](../../../aspose.slides.export/saveformat/), [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[System::Web::HttpResponse](../../../system.web/httpresponse/)\>, **bool**) method


Sends the presentation to the client browser. This method is absent in ClientProfile versions of Aspose.Slide.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options, System::SharedPtr<System::Web::HttpResponse> response, bool showInline)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | The name for the presentation that will appear at the client browser. The name should not contain path. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Additional format options. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[System::Web::HttpResponse](../../../system.web/httpresponse/)\> | Response object where to save the document. |
| showInline | **bool** | True to show an option to open the presentation inside the browser. |

## See Also

* Class [String](../../../system/string/)
* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
