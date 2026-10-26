---
title: get_SlideSize()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar slide size-objekt. Skrivskyddad ISlideSize.
type: docs
weight: 79
url: /sv/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() method


Returnerar slide size-objekt. Skrivskyddad [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Anmärkningar

The following example shows how to change the slide size in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 The following example shows how to set slide size with respect to content scaling for a PowerPoint [Presentation](../). 
```cpp
// Skapa ett Presentation-objekt som representerar en presentationsfil
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Ställ in bildstorleken för genererade presentationer till samma som källan
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// Metoden SetSize används för att sätta bildstorlek med skalning av innehåll för att säkerställa passning
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// Metoden SetSize används för att sätta bildstorlek genom att maximera innehållets storlek
// Spara presentationen till disk
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to specifying custom slide sizes in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// A4-pappersstorlek
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlideSize](../../islidesize/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)