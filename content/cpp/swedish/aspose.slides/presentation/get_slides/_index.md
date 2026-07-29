---
title: get_Slides()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en lista med alla bilder som är definierade i presentationen. Skrivskyddad ISlideCollection.
type: docs
weight: 53
url: /sv/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() metod


Returnerar en lista med alla bilder som är definierade i presentationen. Skrivskyddad [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Anmärkningar


 Följande exempel visar hur man sätter bakgrundsfärgen för bilder i PowerPoint [Presentation](../). 
```cpp
// Instansiera Presentation-klassen som representerar presentationsfilen
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Set the background color of the first ISlide to Blue
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 Följande exempel visar hur man sätter bakgrundsbilden för bilder i PowerPoint [Presentation](../). 
```cpp
// Instansiera Presentation-klassen som representerar presentationsfilen
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Ställ in bakgrunden med bild
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Ställ in bilden
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Lägg till bilden i presentationens bildsamling
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Skriv presentationen till disk
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 Följande exempel visar hur man lägger till bildövergång [Presentation](../). 
```cpp
// Instansiera Presentation-klassen för att läsa in källpresentationsfilen
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Tillämpa cirkeltyp övergång på bild 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Tillämpa comb-typ övergång på bild 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Skriv presentationen till disk
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 Följande exempel visar hur man lägger till avancerad bildövergång. 
```cpp
// Instansiera Presentation-klassen som representerar en presentationsfil
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Tillämpa cirkeltyp övergång på bild 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Ställ in övergångstiden till 3 sekunder
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Tillämpa comb-typ övergång på bild 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Ställ in övergångstiden till 5 sekunder
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Tillämpa zoomtyp övergång på bild 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Ställ in övergångstiden till 7 sekunder
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Skriv presentationen till disk
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlideCollection](../../islidecollection/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)