---
title: get_SlideSize()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert slide size object. Alleen-lezen ISlideSize.
type: docs
weight: 79
url: /nl/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() methode


Retourneert slide size object. Alleen-lezen [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Opmerkingen


Het volgende voorbeeld laat zien hoe u de slide size wijzigt in een PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
Het volgende voorbeeld laat zien hoe u de slide size instelt met betrekking tot inhoudsschaal voor een PowerPoint [Presentation](../). 
```cpp
// Maak een Presentation-object dat een presentatiebestand vertegenwoordigt
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Stel de slide size van de gegenereerde presentaties in op die van de bron
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// Methode SetSize wordt gebruikt om de slide size in te stellen met geschaalde inhoud zodat deze past
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// Methode SetSize wordt gebruikt om de slide size in te stellen met maximale grootte van de inhoud
// Sla Presentation op naar schijf
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
Het volgende voorbeeld laat zien hoe u aangepaste slide sizes specificeert in een PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// A4-papierformaat
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlideSize](../../islidesize/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)