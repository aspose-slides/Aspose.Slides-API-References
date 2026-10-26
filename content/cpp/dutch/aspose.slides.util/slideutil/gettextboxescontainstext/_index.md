---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert alle tekstframes op de opgegeven dia die de opgegeven tekst bevatten.
type: docs
weight: 66
url: /nl/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) methode

Retourneert alle tekstframes op de opgegeven dia die de opgegeven tekst bevatten.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | De dia om te doorzoeken. |
| text | [System::String](../../../system/string/) | De tekst om te zoeken binnen tekstframes. |
| checkPlaceholderText | **bool** | Geeft aan of tekstframes die leeg zijn, maar waarvan de placeholdertekst de zoektekst bevat, moeten worden opgenomen. |

### Retourwaarde

Een array van [ITextFrame](../../../aspose.slides/itextframe/) objecten die de opgegeven tekst bevatten.

## Zie Ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITextFrame](../../../aspose.slides/itextframe/)
* Klasse [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Klasse [String](../../../system/string/)
* Klasse [SlideUtil](../)
* Naamruimte [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)