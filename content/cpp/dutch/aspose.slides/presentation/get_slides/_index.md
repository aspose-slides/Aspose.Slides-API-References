---
title: get_Slides()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd. Alleen-lezen ISlideCollection.
type: docs
weight: 53
url: /nl/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() methode


Retourneert een lijst van alle dia's die zijn gedefinieerd in de presentatie. Alleen-lezen [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Opmerkingen


Het volgende voorbeeld laat zien hoe je de achtergrondkleur van dia's in PowerPoint [Presentation](../) instelt. 
```cpp
// Maak een instantie van de Presentation-klasse die het presentatiebestand vertegenwoordigt
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Stel de achtergrondkleur van de eerste ISlide in op blauw
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 Het volgende voorbeeld laat zien hoe je de achtergrondafbeelding van dia's in PowerPoint [Presentation](../) instelt. 
```cpp
// Maak een instantie van de Presentation-klasse die het presentatiebestand vertegenwoordigt
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Stel de achtergrond in met een afbeelding
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Stel de afbeelding in
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Voeg de afbeelding toe aan de afbeeldingscollectie van de presentatie
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Schrijf de presentatie naar schijf
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 Het volgende voorbeeld laat zien hoe je een diaovergang toevoegt [Presentation](../). 
```cpp
// Maak een instantie van de Presentation-klasse om het bronpresentatiebestand te laden
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Pas een cirkeltype overgang toe op dia 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Pas een kamtype overgang toe op dia 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Schrijf de presentatie naar schijf
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 Het volgende voorbeeld laat zien hoe je een geavanceerde diaovergang toevoegt. 
```cpp
// Maak een instantie van de Presentation-klasse die een presentatiebestand vertegenwoordigt
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Pas een cirkeltype overgang toe op dia 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Stel de overgangstijd in op 3 seconden
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Pas een kamtype overgang toe op dia 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Stel de overgangstijd in op 5 seconden
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Pas een zoomtype overgang toe op dia 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Stel de overgangstijd in op 7 seconden
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Schrijf de presentatie naar schijf
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlideCollection](../../islidecollection/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)