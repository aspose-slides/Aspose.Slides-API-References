---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt gesloten WebVTT-ondertitels toe aan het einde van de collectie.
type: docs
weight: 27
url: /nl/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) methode

Voegt gesloten WebVTT-ondertitels toe aan het einde van de collectie.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Het label van de gesloten ondertitels. |
| filePath | [System::String](../../../system/string/) | Het pad naar het WebVTT-bestand. |

### Retourwaarde

De toegevoegde [ICaptions](../../icaptions/) instantie.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) methode

Voegt gesloten WebVTT-ondertitels toe aan het einde van de collectie vanuit een stream.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Het label van de gesloten ondertitels. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | De invoerstream die gegevens in WebVTT-indeling bevat. |

### Retourwaarde

De toegevoegde [ICaptions](../../icaptions/) instantie.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICaptions](../../icaptions/)
* Klasse [String](../../../system/string/)
* Klasse [CaptionsCollection](../)
* Klasse [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)