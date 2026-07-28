---
title: get_Slides()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a bemutatóban definiált összes dia listáját. Csak olvasható ISlideCollection.
type: docs
weight: 53
url: /hu/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() metódus


Visszaadja a bemutatóban definiált összes dia listáját. Csak olvasható [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Megjegyzések


A következő példa bemutatja, hogyan állítható be a PowerPoint [Presentation](../) dia háttérszíne. 
```cpp
// Példányosítsa a Presentation osztályt, amely a bemutató fájlt képviseli
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Állítsa be az első ISlide háttérszínét kékre
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 A következő példa bemutatja, hogyan állítható be a PowerPoint [Presentation](../) dia háttérképe. 
```cpp
// Példányosítsa a Presentation osztályt, amely a bemutató fájlt képviseli
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Set the background with Image
// Állítsa be a háttérképet képpel
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Set the picture
// Állítsa be a képet
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Add image to presentation's images collection
// Adjon hozzá képet a bemutató képgallériájához
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Write the presentation to disk
// Írja a bemutatót a lemezre
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 A következő példa bemutatja, hogyan adható hozzá diaátmenet [Presentation](../). 
```cpp
// Példányosítja a Presentation osztályt a forrás bemutató fájl betöltéséhez
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Kör típusú átmenetet alkalmaz az 1. dián
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Comb típusú átmenetet alkalmaz a 2. dián
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// A bemutatót lemezre menti
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 A következő példa bemutatja, hogyan adható hozzá fejlett diaátmenet. 
```cpp
// Példányosítja a Presentation osztályt, amely egy bemutató fájlt képvisel
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Kör típusú átmenetet alkalmaz az 1. dián
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Beállítja az átmeneti időt 3 másodpercre
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Comb típusú átmenetet alkalmaz a 2. dián
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Beállítja az átmeneti időt 5 másodpercre
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Zoom típusú átmenetet alkalmaz a 3. dián
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Beállítja az átmeneti időt 7 másodpercre
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// A bemutatót lemezre menti
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlideCollection](../../islidecollection/)
* Osztály [Presentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)