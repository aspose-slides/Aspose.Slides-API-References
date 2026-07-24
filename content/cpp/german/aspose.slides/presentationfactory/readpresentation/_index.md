---
title: ReadPresentation()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest eine vorhandene Präsentation aus einem Array
type: docs
weight: 40
url: /de/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) Methode

Liest eine vorhandene Präsentation aus einem Array

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array zum Lesen |

### Rückgabewert

Gelesene Präsentation

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) Methode

Liest eine vorhandene Präsentation aus einem Array mit zusätzlichen Ladeoptionen

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array zum Lesen |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Ladeoptionen |

### Rückgabewert

Gelesene Präsentation

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) Methode

Liest eine vorhandene Präsentation aus einem Stream

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Eingabestream zum Lesen |

### Rückgabewert

Gelesene Präsentation

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) Methode

Liest eine vorhandene Präsentation aus einem Stream mit zusätzlichen Ladeoptionen

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Eingabestream zum Lesen |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Ladeoptionen |

### Rückgabewert

Gelesene Präsentation

## PresentationFactory::ReadPresentation(System::String) Methode

Liest eine vorhandene Präsentation aus einer Datei

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Dateiname |

### Rückgabewert

Gelesene Präsentation

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) Methode

Liest eine vorhandene Präsentation aus einer Datei mit zusätzlichen Ladeoptionen

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Dateiname |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Ladeoptionen |

### Rückgabewert

Gelesene Präsentation

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IPresentation](../../ipresentation/)
* Klasse [PresentationFactory](../)
* Klasse [ILoadOptions](../../iloadoptions/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)