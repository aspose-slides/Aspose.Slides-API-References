---
title: ReadPresentation()
second_title: Aspose.Slides för C++ API-referens
description: Läser en befintlig presentation från en array
type: docs
weight: 27
url: /sv/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) method


Läser en befintlig presentation från en array

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array att läsa |

### Returvärde

Läs presentation

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) method


Läser en befintlig presentation från en array med ytterligare inläsningsalternativ

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array att läsa |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Inläsningsalternativ |

### Returvärde

Läs presentation

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) method


Läser en befintlig presentation från en ström

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Inmatningsström att läsa |

### Returvärde

Läs presentation

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) method


Läser en befintlig presentation från en ström med ytterligare inläsningsalternativ

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Inmatningsström att läsa |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Inläsningsalternativ |

### Returvärde

Läs presentation

## IPresentationFactory::ReadPresentation(System::String) method


Läser en befintlig presentation från en fil

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Filnamn |

### Returvärde

Läs presentation

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) method


Läser en befintlig presentation från en ström med ytterligare inläsningsalternativ

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Filnamn |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Inläsningsalternativ |

### Returvärde

Läs presentation

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [IPresentation](../../ipresentation/)
* Klass [IPresentationFactory](../)
* Klass [ILoadOptions](../../iloadoptions/)
* Klass [Stream](../../../system.io/stream/)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)