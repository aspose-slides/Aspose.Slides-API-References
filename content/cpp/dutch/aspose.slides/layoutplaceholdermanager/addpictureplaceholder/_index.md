---
title: AddPicturePlaceholder()
second_title: Aspose.Slides voor C++ API Referentie
description: Voegt een nieuw placeholder-vorm toe aan de lay-outslide om een afbeelding te bevatten.
type: docs
weight: 53
url: /nl/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) methode

Voegt een nieuwe placeholder-vorm toe aan de lay-outslide om een afbeelding te bevatten.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | **float** | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | **float** | De breedte van de nieuwe placeholder-vorm. |
| height | **float** | De hoogte van de nieuwe placeholder-vorm. |

### Retourwaarde

Aangemaakt [IAutoShape](../../iautoshape/) met een [Picture](../../picture/) placeholder.

## Opmerkingen

Het volgende voorbeeld toont hoe de [Picture](../../picture/) placeholder-vorm aan de lay-outslide kan worden toegevoegd. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [LayoutPlaceholderManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)