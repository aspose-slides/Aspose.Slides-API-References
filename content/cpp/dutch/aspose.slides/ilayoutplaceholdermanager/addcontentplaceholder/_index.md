---
title: AddContentPlaceholder()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuw plaatshoudervorm toe aan de lay-outdia om inhoud vast te houden, zoals een afbeelding, tabel, media of tekst.
type: docs
weight: 1
url: /nl/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) methode

Voegt een nieuw plaatshoudervorm toe aan de lay-outdia om inhoud vast te houden, zoals een afbeelding, tabel, media of tekst.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De X-coördinaat van de nieuwe plaatshoudervorm. |
| y | **float** | De Y-coördinaat van de nieuwe plaatshoudervorm. |
| width | **float** | De breedte van de nieuwe plaatshoudervorm. |
| height | **float** | De hoogte van de nieuwe plaatshoudervorm. |

### Returnwaarde

Gemaakt [IAutoShape](../../iautoshape/) met een Content-plaatshouder.

## Opmerkingen

Het volgende voorbeeld laat zien hoe de Content-plaatshoudervorm aan de lay-outdia toe te voegen. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ILayoutPlaceholderManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)