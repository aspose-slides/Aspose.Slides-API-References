---
title: AddTablePlaceholder()
second_title: Aspose.Slides voor C++ API Referentie
description: Voegt een nieuwe placeholder-vorm toe aan de lay-outdia om een tabel te bevatten.
type: docs
weight: 79
url: /nl/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) methode


Voegt een nieuwe placeholder-vorm toe aan de lay-outdia om een tabel te bevatten.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | **float** | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | **float** | De breedte van de nieuwe placeholder-vorm. |
| height | **float** | De hoogte van de nieuwe placeholder-vorm. |

### Retourwaarde

Aangemaakt [IAutoShape](../../iautoshape/) met een [Table](../../table/) placeholder.
## Opmerkingen



Het volgende voorbeeld laat zien hoe de [Table](../../table/) placeholder-vorm kan worden toegevoegd aan de lay-outdia. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ILayoutPlaceholderManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)