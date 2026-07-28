---
title: get_Masters()
second_title: Aspose.Slides dla C++ – Referencja API
description: Zwraca listę wszystkich slajdów głównych, które są zdefiniowane w prezentacji. Tylko do odczytu IMasterSlideCollection.
type: docs
weight: 118
url: /pl/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() metoda

Zwraca listę wszystkich slajdów głównych, które są zdefiniowane w prezentacji. Tylko do odczytu [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Uwagi

Poniższe przykłady pokazują, jak dodać [Images](../../images/) do Master [Slides](../../) w PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
Poniższe przykłady pokazują, jak zmienić kolor tła slajdu głównego w PowerPoint [Presentation](../).
```cpp
// Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
auto pres = System::MakeObject<Presentation>();

// Ustaw kolor tła Master ISlide na zielony leśny
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Zapisz prezentację na dysku
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
Poniższe przykłady pokazują, jak dodać układ slajdu do PowerPoint [Presentation](../).
```cpp
// Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Spróbuj wyszukać po typie układu slajdu
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Sytuacja, w której prezentacja nie zawiera pewnych typów układów.
    // Plik prezentacji zawiera tylko typy układów Blank i Custom.
    // Jednak układy slajdów typu Custom mają różne nazwy slajdów,
    // takie jak "Title", "Title and Content" itp. i można ich używać
    // jako nazw do wyboru układu slajdu.
    // Można także użyć zestawu typów kształtów placeholderów. Na przykład,
    // Slajd tytułowy powinien mieć tylko typ placeholdera Title, itp.
    for (auto&& titleAndObjectLayoutSlide : layoutSlides)
    {
        if (titleAndObjectLayoutSlide->get_Name() == u"Title and Object")
        {
            layoutSlide = titleAndObjectLayoutSlide;
            break;
        }
    }

    if (layoutSlide == nullptr)
    {
        for (auto&& titleLayoutSlide : layoutSlides)
        {
            if (titleLayoutSlide->get_Name() == u"Title")
            {
                layoutSlide = titleLayoutSlide;
                break;
            }
        }

        if (layoutSlide == nullptr)
        {
            layoutSlide = layoutSlides->GetByType(SlideLayoutType::Blank);
            if (layoutSlide == nullptr)
            {
                layoutSlide = layoutSlides->Add(SlideLayoutType::TitleAndObject, u"Title and Object");
            }
        }
    }
}

// Dodawanie pustego slajdu z dodanym układem slajdu
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Zapisz prezentację
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMasterSlideCollection](../../imasterslidecollection/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)