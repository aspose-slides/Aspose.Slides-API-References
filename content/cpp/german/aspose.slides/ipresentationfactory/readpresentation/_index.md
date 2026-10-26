---
title: ReadPresentation()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest eine vorhandene Präsentation aus einem Array
type: docs
weight: 27
url: /de/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) Methode

Liest eine vorhandene Präsentation aus einem Array

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array zum Lesen |

### Rückgabewert

Geladene Präsentation

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) Methode

Liest eine vorhandene Präsentation aus einem Array mit zusätzlichen Ladeoptionen

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array zum Lesen |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Ladeoptionen |

### Rückgabewert

Geladene Präsentation

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) Methode

Liest eine vorhandene Präsentation aus einem Stream

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Eingabestream zum Lesen |

### Rückgabewert

Geladene Präsentation

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) Methode

Liest eine vorhandene Präsentation aus einem Stream mit zusätzlichen Ladeoptionen

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Eingabestream zum Lesen |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Ladeoptionen |

### Rückgabewert

Geladene Präsentation

## IPresentationFactory::ReadPresentation(System::String) Methode

Liest eine vorhandene Präsentation aus einer Datei

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Dateiname |

### Rückgabewert

Geladene Präsentation

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) Methode

Liest eine vorhandene Präsentation aus einer Datei mit zusätzlichen Ladeoptionen

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Dateiname |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Ladeoptionen |

### Rückgabewert

Geladene Präsentation

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPresentation](../../ipresentation/)
* Class [IPresentationFactory](../)
* Class [ILoadOptions](../../iloadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)