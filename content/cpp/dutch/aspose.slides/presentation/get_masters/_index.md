---
title: get_Masters()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een lijst met alle master-dia's die in de presentatie zijn gedefinieerd. Alleen-lezen IMasterSlideCollection.
type: docs
weight: 118
url: /nl/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() methode


Retourneert een lijst met alle master-dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Opmerkingen


De volgende voorbeelden laten zien hoe [Images](../../images/) toe te voegen aan Master [Slides](../../) van PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
 De volgende voorbeelden laten zien hoe de achtergrondkleur van de master-dia van PowerPoint [Presentation](../) te wijzigen. 
```cpp
// Instantieer de Presentation-klasse die het presentatiebestand vertegenwoordigt
auto pres = System::MakeObject<Presentation>();

// Stel de achtergrondkleur van de Master ISlide in op bosgroen
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Schrijf de presentatie naar de schijf
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
 De volgende voorbeelden laten zien hoe een dia-indeling toe te voegen aan PowerPoint [Presentation](../). 
```cpp
// Instantieer de Presentation-klasse die het presentatiebestand vertegenwoordigt
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Probeer te zoeken op layout-dia type
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // De situatie waarin een presentatie niet een bepaald type lay-outs bevat.
    // Het presentatiebestand bevat alleen lege en aangepaste layout-types.
    // Maar layout-dia's met aangepaste types hebben verschillende dia-namen,
    // zoals "Title", "Title and Content", enz. En het is mogelijk om deze
    // namen te gebruiken voor het selecteren van een layout-dia.
    // Ook is het mogelijk om de set van placeholder-vormtypes te gebruiken. Bijvoorbeeld,
    // Een titeldia moet alleen een Title placeholder-type hebben, enz.
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

// Voeg een lege dia toe met de toegevoegde layout-dia
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Sla de presentatie op
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMasterSlideCollection](../../imasterslidecollection/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)