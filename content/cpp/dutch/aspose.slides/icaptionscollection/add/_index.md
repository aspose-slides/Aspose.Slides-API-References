---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt WebVTT-gesloten ondertitels toe aan het einde van de collectie.
type: docs
weight: 27
url: /nl/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) methode

Voegt WebVTT-gesloten ondertitels toe aan het einde van de collectie.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Het label van de gesloten ondertitels. |
| filePath | [System::String](../../../system/string/) | Het pad naar het WebVTT-bestand. |

### Retourwaarde

De toegevoegde [ICaptions](../../icaptions/) instantie.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) methode

Voegt WebVTT-gesloten ondertitels toe aan het einde van de collectie vanuit een stream.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Het label van de gesloten ondertitels. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | De invoerstroom met gegevens in WebVTT-formaat. |

### Retourwaarde

De toegevoegde [ICaptions](../../icaptions/) instantie.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICaptions](../../icaptions/)
* Klasse [String](../../../system/string/)
* Klasse [ICaptionsCollection](../)
* Klasse [Stream](../../../system.io/stream/)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)