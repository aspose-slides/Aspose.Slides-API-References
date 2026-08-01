---
title: AddMediaPlaceholder()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuwe placeholdervorm toe aan de lay-out slide om een media-object te bevatten.
type: docs
weight: 105
url: /nl/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---
## ILayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) method

Voegt een nieuw placeholder-vorm toe aan de layout-slide om een media-object te bevatten.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | **float** | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | **float** | De breedte van de nieuwe placeholder-vorm. |
| height | **float** | De hoogte van de nieuwe placeholder-vorm. |

### Retourwaarde

Aangemaakt [IAutoShape](../../iautoshape/) met een Media-placeholder.

## Opmerkingen

Het volgende voorbeeld toont hoe je de Media-placeholder-vorm toevoegt aan de layout-slide. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ILayoutPlaceholderManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)