---
title: get_SlideSize()
second_title: Aspose.Slides for C++ API-referencia
description: Visszaadja a dia méret objektumot. Csak olvasható ISlideSize.
type: docs
weight: 79
url: /hu/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() metódus


Visszaadja a dia méret objektumot. Csak olvasható [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Megjegyzések


Az alábbi példa azt mutatja, hogyan lehet módosítani a dia méretét egy PowerPoint [Presentation](../)-ban. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 A következő példa azt mutatja, hogyan lehet beállítani a dia méretét a tartalom méretezéséhez egy PowerPoint [Presentation](../)-ban. 
```cpp
// Egy Presentation objektum példányosítása, amely egy prezentációfájlt képvisel
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// A generált prezentációk diaméretének beállítása a forráséhoz
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// A SetSize metódus a diaméret beállításához használatos, a tartalom méretezésével, hogy biztosan illeszkedjen
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// A SetSize metódus a diaméret beállításához használatos, a tartalom méretének maximalizálásával
// A prezentáció mentése a lemezre
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 A következő példa azt mutatja, hogyan lehet egyedi dia méreteket megadni egy PowerPoint [Presentation](../)-ban. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// A4 papírméret
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlideSize](../../islidesize/)
* Osztály [Presentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)