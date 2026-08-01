---
title: GetPresentationInfo()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt een nieuw PresentationInfo object aan vanuit een bestand en bindt de presentatie eraan.
type: docs
weight: 27
url: /nl/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) methode

Maakt een nieuw [PresentationInfo](../../presentationinfo/) object aan vanuit bestand en bindt de presentatie eraan.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) bestand. |

### Retourwaarde

[Presentation](../../presentation/) informatie gebonden aan de presentatie.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) methode

Maakt een nieuw [PresentationInfo](../../presentationinfo/) object aan vanuit stream en bindt de presentatie eraan. Haalt informatie over de presentatie op in de opgegeven stream.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) stream. |

### Retourwaarde

[Presentation](../../presentation/) informatie gebonden aan de presentatie.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPresentationInfo](../../ipresentationinfo/)
* Klasse [String](../../../system/string/)
* Klasse [PresentationFactory](../)
* Klasse [Stream](../../../system.io/stream/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)