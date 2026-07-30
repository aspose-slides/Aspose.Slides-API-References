---
title: get_Slides()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrátí seznam všech snímků, které jsou v prezentaci definovány. Pouze pro čtení ISlideCollection.
type: docs
weight: 53
url: /cs/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() metoda


Vrátí seznam všech snímků, které jsou v prezentaci definovány. Pouze pro čtení [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Poznámky


Následující příklad ukazuje, jak nastavit barvu pozadí snímků v PowerPointu [Presentation](../). 
```cpp
// Vytvořte instanci třídy Presentation, která reprezentuje soubor prezentace
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Nastavte barvu pozadí prvního ISlide na modrou
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 Následující příklad ukazuje, jak nastavit obrázek pozadí snímků v PowerPointu [Presentation](../). 
```cpp
// Vytvořte instanci třídy Presentation, která představuje soubor prezentace
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Nastavte pozadí pomocí obrázku
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Nastavte obrázek
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Přidejte obrázek do kolekce obrázků prezentace
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Zapište prezentaci na disk
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 Následující příklad ukazuje, jak přidat přechod snímku [Presentation](../). 
```cpp
// Vytvořte instanci třídy Presentation pro načtení zdrojového souboru prezentace
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Použijte přechod typu kruh na snímku 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Použijte přechod typu hřeben na snímku 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Zapište prezentaci na disk
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 Následující příklad ukazuje, jak přidat pokročilý přechod snímku. 
```cpp
// Vytvořte instanci třídy Presentation, která představuje soubor prezentace
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Použijte přechod typu kruh na snímku 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Nastavte dobu trvání přechodu na 3 sekundy
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Použijte přechod typu hřeben na snímku 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Nastavte dobu trvání přechodu na 5 sekund
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Použijte přechod typu zoom na snímku 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Nastavte dobu trvání přechodu na 7 sekund
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Zapište prezentaci na disk
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlideCollection](../../islidecollection/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)