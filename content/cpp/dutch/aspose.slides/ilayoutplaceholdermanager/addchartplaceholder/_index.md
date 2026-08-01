---
title: AddChartPlaceholder()
second_title: Aspose.Slides for C++ API Referentie
description: Voegt een nieuw placeholder-vorm toe aan de layout-dia om een chart te bevatten.
type: docs
weight: 66
url: /nl/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) methode

Voegt een nieuw placeholder-vorm toe aan de layout-dia om een Chart te bevatten.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | **float** | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | **float** | De breedte van de nieuwe placeholder-vorm. |
| height | **float** | De hoogte van de nieuwe placeholder-vorm. |

### Retourwaarde

Aangemaakt [IAutoShape](../../iautoshape/) met een Chart placeholder.

## Opmerkingen

Het volgende voorbeeld laat zien hoe de Chart placeholder-vorm aan de layout-dia kan worden toegevoegd. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ILayoutPlaceholderManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)