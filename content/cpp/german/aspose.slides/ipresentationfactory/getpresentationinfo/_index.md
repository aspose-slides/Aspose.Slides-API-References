---
title: GetPresentationInfo()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt Informationen über die Präsentation in der angegebenen Datei.
type: docs
weight: 14
url: /de/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) Methode


Ermittelt Informationen über die Präsentation in der angegebenen Datei.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) Datei. |

### Rückgabewert

[Presentation](../../presentation/) Info

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) Methode


Ermittelt Informationen über die Präsentation im angegebenen Stream.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) Stream. |

### Rückgabewert

[Presentation](../../presentation/) Info

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationInfo](../../ipresentationinfo/)
* Class [String](../../../system/string/)
* Class [IPresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)