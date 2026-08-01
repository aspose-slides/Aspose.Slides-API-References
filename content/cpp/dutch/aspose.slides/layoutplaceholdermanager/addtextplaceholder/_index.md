---
title: AddTextPlaceholder()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuw placeholder-vorm toe aan de layout slide om tekstinhoud vast te houden.
type: docs
weight: 27
url: /nl/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) methode

Voegt een nieuw placeholder-vorm toe aan de layout-slide om tekstinhoud vast te houden.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De X-coördinate van de nieuwe placeholder-vorm. |
| y | **float** | De Y-coördinate van de nieuwe placeholder-vorm. |
| width | **float** | De breedte van de nieuwe placeholder-vorm. |
| height | **float** | De hoogte van de nieuwe placeholder-vorm. |

### Retourwaarde

Gemaakt [IAutoShape](../../iautoshape/) met een Text placeholder.

## Opmerkingen

Het volgende voorbeeld toont hoe de Text placeholder-vorm aan de layout-slide kan worden toegevoegd.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [LayoutPlaceholderManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)