---
title: get_Slides()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Nur-Lesen ISlideCollection.
type: docs
weight: 53
url: /de/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() Methode


Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Nur-Lesen [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Hinweise


 Das folgende Beispiel zeigt, wie man die Hintergrundfarbe von Folien in PowerPoint [Presentation](../) einstellt. 
```cpp
// Instanziieren Sie die Presentation-Klasse, die die Präsentationsdatei darstellt
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Set the background color of the first ISlide to Blue
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 Das folgende Beispiel zeigt, wie man das Hintergrundbild von Folien in PowerPoint [Presentation](../) festlegt. 
```cpp
// Instanziieren Sie die Presentation-Klasse, die die Präsentationsdatei darstellt
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Setzen Sie den Hintergrund mit einem Bild
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Setzen Sie das Bild
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Fügen Sie das Bild zur Bildersammlung der Präsentation hinzu
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Schreiben Sie die Präsentation auf die Festplatte
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 Das folgende Beispiel zeigt, wie man einen Folienübergang [Presentation](../) hinzufügt. 
```cpp
// Instanziieren Sie die Presentation-Klasse, um die Quelldatei der Präsentation zu laden
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Wenden Sie den Kreis-Übergang auf Folie 1 an
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Wenden Sie den Kamm-Übergang auf Folie 2 an
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Speichern Sie die Präsentation auf die Festplatte
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 Das folgende Beispiel zeigt, wie man einen erweiterten Folienübergang hinzufügt. 
```cpp
// Instanziieren Sie die Presentation-Klasse, die eine Präsentationsdatei darstellt
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Wenden Sie den Kreis-Übergang auf Folie 1 an
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Setzen Sie die Übergangszeit auf 3 Sekunden
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Wenden Sie den Kamm-Übergang auf Folie 2 an
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Setzen Sie die Übergangszeit auf 5 Sekunden
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Wenden Sie den Zoom-Übergang auf Folie 3 an
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Setzen Sie die Übergangszeit auf 7 Sekunden
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Speichern Sie die Präsentation auf die Festplatte
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlideCollection](../../islidecollection/)
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)