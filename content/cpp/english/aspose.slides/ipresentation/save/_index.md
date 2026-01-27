---
title: Save()
second_title: Aspose.Slides for C++ API Reference
description: Saves all slides of a presentation to a file with the specified format.
type: docs
weight: 404
url: /aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) method


Saves all slides of a presentation to a file with the specified format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Path to the created file. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) method


Saves all slides of a presentation to a stream in the specified format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Output stream. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


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

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


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

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method


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

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


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

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method


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

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


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

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) method


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

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IPresentation](../)
* Class [Stream](../../../system.io/stream/)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)