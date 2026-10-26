---
title: GetPresentationInfo()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt ein neues PresentationInfo-Objekt aus einer Datei und bindet die Präsentation daran.
type: docs
weight: 27
url: /de/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) Methode

Erstellt ein neues [PresentationInfo](../../presentationinfo/)-Objekt aus einer Datei und bindet die Präsentation daran.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) Datei. |

### Rückgabewert

[Presentation](../../presentation/) Info, die an die Präsentation gebunden ist.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) Methode

Erstellt ein neues [PresentationInfo](../../presentationinfo/)-Objekt aus dem Stream und bindet die Präsentation daran. Ermittelt Informationen über die Präsentation im angegebenen Stream.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) Stream. |

### Rückgabewert

[Presentation](../../presentation/) Info, die an die Präsentation gebunden ist.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPresentationInfo](../../ipresentationinfo/)
* Klasse [String](../../../system/string/)
* Klasse [PresentationFactory](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)