---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuw placeholdervorm toe aan de lay-outdia om inhoud vast te houden, zoals een afbeelding, tabel, media of tekst in een verticale richting.
type: docs
weight: 14
url: /nl/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) methode

Voegt een nieuwe placeholdervorm toe aan de lay-outdia om inhoud vast te houden, zoals een afbeelding, tabel, media of tekst in een verticale richting.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De X-coördinate van de nieuwe placeholdervorm. |
| y | **float** | De Y-coördinate van de nieuwe placeholdervorm. |
| width | **float** | De breedte van de nieuwe placeholdervorm. |
| height | **float** | De hoogte van de nieuwe placeholdervorm. |

### Retourwaarde

Aangemaakt [IAutoShape](../../iautoshape/) met een Content (Vertical) placeholder.

## Opmerkingen

Het volgende voorbeeld toont hoe de Content (Vertical) placeholdervorm aan de lay-outdia kan worden toegevoegd. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ILayoutPlaceholderManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)