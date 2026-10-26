---
title: get_Masters()
second_title: Aspose.Slides pro C++ referenci API
description: Vrací seznam všech hlavních snímků, které jsou definovány v prezentaci. Pouze ke čtení IMasterSlideCollection.
type: docs
weight: 118
url: /cs/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() metoda


Vrací seznam všech hlavních snímků, které jsou definovány v prezentaci. Pouze ke čtení [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Poznámky


Následující příklady ukazují, jak přidat [Images](../../images/) do hlavního snímku [Slides](../../) v PowerPointu [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
 Následující příklady ukazují, jak změnit barvu pozadí hlavního snímku v PowerPointu [Presentation](../). 
```cpp
// Vytvořte instanci třídy Presentation, která představuje soubor prezentace
auto pres = System::MakeObject<Presentation>();

// Nastavte barvu pozadí hlavního ISlide na lesní zelenou
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Zapište prezentaci na disk
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
 Následující příklady ukazují, jak přidat rozložení snímku do PowerPointu [Presentation](../). 
```cpp
// Vytvořte instanci třídy Presentation, která představuje soubor prezentace
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Zkuste vyhledat podle typu rozvržení snímku
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Situace, kdy prezentace neobsahuje určitý typ rozvržení.
    // Soubor prezentace obsahuje pouze typy rozvržení Blank a Custom.
    // Ale rozvržení snímků s typy Custom mají různé názvy snímků,
    // např. "Title", "Title and Content", atd. A je možné použít tyto
    // názvy pro výběr rozvržení snímku.
    // Také je možné použít sadu typů placeholder tvarů. Například,
    // Snímek Title by měl mít jen typ placeholderu Title, atd.
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

// Přidání prázdného snímku s přidaným rozvržením snímku
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Uložit prezentaci
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMasterSlideCollection](../../imasterslidecollection/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)