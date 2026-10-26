---
title: get_Masters()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaad egy listát az előadásban definiált összes mesterdiáról. Írásvédett IMasterSlideCollection.
type: docs
weight: 118
url: /hu/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() metódus

Visszaad egy listát az összes mesterdiáról, amely a bemutatóban van definiálva. Írásvédett [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Megjegyzések

A következő példák bemutatják, hogyan kell [Images](../../images/) hozzáadni a PowerPoint [Presentation](../) [Slides](../../) mesteréhez.
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
A következő példák bemutatják, hogyan lehet megváltoztatni a PowerPoint [Presentation](../) mesterdiájának háttérszínét.
```cpp
// Hozza létre a Presentation osztályt, amely a prezentációs fájlt képviseli
auto pres = System::MakeObject<Presentation>();

// Állítsa be a Master ISlide háttérszínét erdei zöldre
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Mentse a prezentációt a lemezre
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
A következő példák bemutatják, hogyan lehet diaelrendezést hozzáadni a PowerPoint [Presentation](../)-hez.
```cpp
// Példányosítsa a Presentation osztályt, amely a prezentációs fájlt képviseli
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Próbáljon meg keresni diaképarendezés típusa alapján
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Az a helyzet, amikor egy prezentáció nem tartalmaz bizonyos típusú elrendezéseket.
    // A prezentációfájl csak Üres és Egyedi elrendezés típusokat tartalmaz.
    // Azonban az Egyedi típusú elrendezésdiák különböző dianevekkel rendelkeznek,
    // például "Title", "Title and Content", stb. És lehetséges ezeket
    // a nevek az elrendezésdia kiválasztásához.
    // Ezenkívül lehetséges a helykitöltő alakzat típusok halmazát használni. Például,
    // A cím dia csak Cím helykitöltő típussal rendelkezhet, stb.
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

// Üres dia hozzáadása a hozzáadott elrendezésdiával
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Mentse a prezentációt
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMasterSlideCollection](../../imasterslidecollection/)
* Osztály [Presentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)