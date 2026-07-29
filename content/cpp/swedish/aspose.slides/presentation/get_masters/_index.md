---
title: get_Masters()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en lista med alla masterslides som är definierade i presentationen. Skrivskyddad IMasterSlideCollection.
type: docs
weight: 118
url: /sv/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() metod

Returnerar en lista med alla masterslides som är definierade i presentationen. Skrividskyddad [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Anmärkningar

Följande exempel visar hur man lägger till [Images](../../images/) till Master [Slides](../../) i PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
Följande exempel visar hur man ändrar bakgrundsfärgen på mastersliden i PowerPoint [Presentation](../). 
```cpp
// Instansiera Presentation-klassen som representerar presentationsfilen
auto pres = System::MakeObject<Presentation>();

// Ange bakgrundsfärgen för Master ISlide till skoggrön
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Skriv presentationen till disk
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
Följande exempel visar hur man lägger till bildlayout i PowerPoint [Presentation](../). 
```cpp
// Instansiera Presentation-klassen som representerar presentationsfilen
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Försök att söka efter layoutslide-typ
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Situationen när en presentation inte innehåller vissa typer av layouter.
    // presentationsfilen innehåller bara tomma och anpassade layouttyper.
    // Men layoutslides med anpassade typer har olika slidnamn,
    // som "Title", "Title and Content", osv. Och det är möjligt att använda dessa
    // namn för val av layoutslide.
    // Det är också möjligt att använda uppsättningen av platshållarformstyper. Till exempel,
    // Titelsliden bör bara ha Title-plats hållare-typ, etc.
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

// Lägger till en tom slide med den tillagda layoutsliden
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Spara presentationen
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMasterSlideCollection](../../imasterslidecollection/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)