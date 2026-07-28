---
title: get_Slides()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca listę wszystkich slajdów, które są zdefiniowane w prezentacji. Tylko do odczytu ISlideCollection.
type: docs
weight: 53
url: /pl/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() metoda

Zwraca listę wszystkich slajdów, które są zdefiniowane w prezentacji. Tylko do odczytu [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Uwagi

Poniższy przykład pokazuje, jak ustawić kolor tła slajdów w programie PowerPoint [Presentation](../).
```cpp
// Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Set the background color of the first ISlide to Blue
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
Poniższy przykład pokazuje, jak ustawić obraz tła slajdów w programie PowerPoint [Presentation](../).
```cpp
// Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Ustaw tło przy użyciu obrazu
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Ustaw obraz
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Dodaj obraz do kolekcji obrazów prezentacji
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Zapisz prezentację na dysku
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
Poniższy przykład pokazuje, jak dodać przejście slajdu [Presentation](../).
```cpp
// Utwórz instancję klasy Presentation, aby wczytać źródłowy plik prezentacji
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Zastosuj przejście typu circle na slajdzie 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Zastosuj przejście typu comb na slajdzie 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Zapisz prezentację na dysku
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
Poniższy przykład pokazuje, jak dodać zaawansowane przejście slajdu.
```cpp
// Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Zastosuj przejście typu circle na slajdzie 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Ustaw czas trwania przejścia na 3 sekundy
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Zastosuj przejście typu comb na slajdzie 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Ustaw czas trwania przejścia na 5 sekund
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Zastosuj przejście typu zoom na slajdzie 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Ustaw czas trwania przejścia na 7 sekund
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Zapisz prezentację na dysku
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlideCollection](../../islidecollection/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)