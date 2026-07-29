---
title: ReadPresentation()
second_title: Aspose.Slides för C++ API-referens
description: Läser en befintlig presentation från en array
type: docs
weight: 40
url: /sv/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metod


Läser en befintlig presentation från en array

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array to read |

### Returvärde

Läs presentation

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metod


Läser en befintlig presentation från en array med ytterligare inläsningsalternativ

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array to read |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### Returvärde

Läs presentation

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metod


Läser en befintlig presentation från en ström

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream to read |

### Returvärde

Läs presentation

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metod


Läser en befintlig presentation från en ström med ytterligare inläsningsalternativ

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream to read |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### Returvärde

Läs presentation

## PresentationFactory::ReadPresentation(System::String) metod


Läser en befintlig presentation från en fil

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | File name |

### Returvärde

Läs presentation

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metod


Läser en befintlig presentation från en fil med ytterligare inläsningsalternativ

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | File name |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### Returvärde

Läs presentation

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPresentation](../../ipresentation/)
* Class [PresentationFactory](../)
* Class [ILoadOptions](../../iloadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)