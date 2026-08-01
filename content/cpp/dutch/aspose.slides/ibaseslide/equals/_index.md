---
title: Equals()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de dia. Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, bijv. SlideId, en dynamische inhoud, bijv. de huidige datumwaarde in Date Placeholder.
type: docs
weight: 183
url: /nl/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) methode

Bepaalt of de twee [IBaseSlide](../) instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de dia. Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, bijv. SlideId, en dynamische inhoud, bijv. de huidige datumwaarde in Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | De [IBaseSlide](../) om te vergelijken met de huidige [IBaseSlide](../). |

### Retourwaarde

**true** als de opgegeven [IBaseSlide](../) gelijk is aan de huidige [IBaseSlide](../); anders **false**.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBaseSlide](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)