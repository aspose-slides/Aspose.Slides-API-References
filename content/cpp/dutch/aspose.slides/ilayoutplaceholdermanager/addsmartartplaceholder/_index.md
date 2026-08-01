---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuwe placeholder-vorm toe aan de layout-dia om een SmartArt-diagram vast te houden.
type: docs
weight: 92
url: /nl/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) methode

Voegt een nieuwe placeholder-vorm toe aan de layout-dia om een [SmartArt](../../../aspose.slides.smartart/) diagram vast te houden.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | **float** | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | **float** | De breedte van de nieuwe placeholder-vorm. |
| height | **float** | De hoogte van de nieuwe placeholder-vorm. |

### Retourwaarde

Aangemaakt [IAutoShape](../../iautoshape/) met een [SmartArt](../../../aspose.slides.smartart/) placeholder.

## Opmerkingen

Het volgende voorbeeld toont hoe de [SmartArt](../../../aspose.slides.smartart/) placeholder-vorm toegevoegd kan worden aan de layout-dia. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)