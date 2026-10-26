---
title: Hyperlink()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een instantie van een hyperlink aan.
type: docs
weight: 339
url: /nl/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) constructor

Maakt een instantie van een hyperlink aan.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) constructor

Maakt een instantie van een hyperlink die naar een specifieke dia wijst. Opmerking: de gemaakte hyperlink moet aan een object uit dezelfde presentatie worden toegewezen, anders wordt de link opgeslagen als NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Doeldia. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) constructor

Maakt een instantie van een hyperlink met een andere hyperlink als bron, waarbij secundaire eigenschappen worden overschreven.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Bron-hyperlink |
| targetFrame | [System::String](../../../system/string/) | Doelframe |
| tooltip | [System::String](../../../system/string/) | Tooltip-tekst |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Hyperlink](../)
* Klasse [ISlide](../../islide/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)