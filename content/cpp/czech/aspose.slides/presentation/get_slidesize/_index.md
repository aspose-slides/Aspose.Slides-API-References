---
title: get_SlideSize()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací objekt velikosti snímku. Pouze ke čtení ISlideSize.
type: docs
weight: 79
url: /cs/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() metoda

Vrací objekt velikosti snímku. Pouze ke čtení [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Poznámky

Následující příklad ukazuje, jak změnit velikost snímku v PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
Následující příklad ukazuje, jak nastavit velikost snímku s ohledem na škálování obsahu pro PowerPoint [Presentation](../). 
```cpp
// Vytvořte objekt Presentation, který představuje soubor prezentace
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Nastavte velikost snímku vygenerovaných prezentací na velikost zdroje
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// Metoda SetSize se používá pro nastavení velikosti snímku se škálováním obsahu, aby se zajistilo přizpůsobení
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// Metoda SetSize se používá pro nastavení velikosti snímku s maximalizací velikosti obsahu
// Uložte prezentaci na disk
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
Následující příklad ukazuje, jak určit vlastní velikosti snímků v PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// Velikost papíru A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlideSize](../../islidesize/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)