---
title: Save()
second_title: Aspose.Slides för C++ API-referens
description: Sparar alla bilder i en presentation till en fil med det angivna formatet.
type: docs
weight: 404
url: /sv/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) metod

Sparar alla bilder i en presentation till en fil med det angivna formatet.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Sökväg till den skapade filen. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format för de exporterade data. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) metod

Sparar alla bilder i en presentation till en ström i det angivna formatet.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Utmatningsström. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format för de exporterade data. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metod

Sparar alla bilder i en presentation till en fil med det angivna formatet och med ytterligare alternativ.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Sökväg till den skapade filen. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format för de exporterade data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Ytterligare formatalternativ. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metod

Sparar alla bilder i en presentation till en ström i det angivna formatet och med ytterligare alternativ.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Utmatningsström. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format för de exporterade data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Ytterligare formatalternativ. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) metod

Sparar angivna bilder i en presentation till en fil med det angivna formatet.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Sökväg till den skapade filen. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array med bildpositioner, med början från 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format för de exporterade data. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metod

Sparar angivna bilder i en presentation till en fil med det angivna formatet.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Sökväg till den skapade filen. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array med bildpositioner, med början från 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format för de exporterade data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Ytterligare formatalternativ. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) metod

Sparar angivna bilder i en presentation till en ström i det angivna formatet.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Utmatningsström. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array med bildpositioner, med början från 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format för de exporterade data. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metod

Sparar angivna bilder i en presentation till en ström i det angivna formatet.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Utmatningsström. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array med bildpositioner, med början från 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format för de exporterade data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Ytterligare formatalternativ. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) metod

Sparar alla bilder i en presentation till ett antal filer som representerar XAML-markup.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | XAML-formatalternativen. |
## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## Se även

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