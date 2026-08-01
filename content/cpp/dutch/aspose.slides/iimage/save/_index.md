---
title: Save()
second_title: Aspose.Slides voor C++ API-referentie
description: Slaat de afbeelding op in een bestand.
type: docs
weight: 40
url: /nl/aspose.slides/iimage/save/
---
## IImage::Save(System::String) methode


Slaat de afbeelding op in een bestand.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Het pad naar het bestand waarin de afbeelding wordt opgeslagen. |

## IImage::Save(System::String, ImageFormat) methode


Slaat de afbeelding op in een bestand in het opgegeven formaat.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Het pad naar het bestand waarin de afbeelding wordt opgeslagen. |
| format | [ImageFormat](../../imageformat/) | Het afbeeldingformaat. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) methode


Slaat de afbeelding op in een stream in het opgegeven formaat.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | De stream waarin de afbeelding wordt opgeslagen. |
| format | [ImageFormat](../../imageformat/) | Het afbeeldingformaat. |

## IImage::Save(System::String, ImageFormat, int32_t) methode


Slaat de afbeelding op in een bestand in het opgegeven formaat en kwaliteit.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Het pad naar het bestand waarin de afbeelding wordt opgeslagen. |
| format | [ImageFormat](../../imageformat/) | Het afbeeldingformaat. |
| quality | **int32_t** | De kwaliteit van de opgeslagen afbeelding (0 tot 100). 

 Deze parameter heeft alleen invloed op het opslaan in [ImageFormat::Jpeg](../../imageformat/); voor alle andere formaten wordt deze genegeerd. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) methode


Slaat de afbeelding op in een stream in het opgegeven formaat en kwaliteit.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | De stream waarin de afbeelding wordt opgeslagen. |
| format | [ImageFormat](../../imageformat/) | Het afbeeldingformaat. |
| quality | **int32_t** | De kwaliteit van de opgeslagen afbeelding (0 tot 100). 

 Deze parameter heeft alleen invloed op het opslaan in [ImageFormat::Jpeg](../../imageformat/); voor alle andere formaten wordt deze genegeerd. |

## Zie ook

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [IImage](../)
* Klasse [Stream](../../../system.io/stream/)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)