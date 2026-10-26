---
title: AddTablePlaceholder()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuwe placeholdervorm toe aan de lay-outdia om een tabel te bevatten.
type: docs
weight: 79
url: /nl/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) methode

Voegt een nieuw placeholdervorm toe aan de lay-out-dia om een tabel te bevatten.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De X-coördinate van de nieuwe placeholdervorm. |
| y | **float** | De Y-coördinate van de nieuwe placeholdervorm. |
| width | **float** | De breedte van de nieuwe placeholdervorm. |
| height | **float** | De hoogte van de nieuwe placeholdervorm. |

### Retourwaarde

Aangemaakt [IAutoShape](../../iautoshape/) met een [Table](../../table/) placeholder.

## Opmerkingen

Het volgende voorbeeld toont hoe de [Table](../../table/) placeholdervorm aan de lay-out-dia kan worden toegevoegd. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)