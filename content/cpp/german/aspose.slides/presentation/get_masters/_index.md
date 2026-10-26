---
title: get_Masters()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt eine Liste aller Masterfolien zurück, die in der Präsentation definiert sind. Nur-Lesen IMasterSlideCollection.
type: docs
weight: 118
url: /de/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() Methode

Gibt eine Liste aller Masterfolien zurück, die in der Präsentation definiert sind. Nur-Lesen [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Hinweise

Das folgende Beispiel zeigt, wie man [Images](../../images/) zu Master [Slides](../../) von PowerPoint [Presentation](../) hinzufügt. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
Das folgende Beispiel zeigt, wie man die Hintergrundfarbe der Masterfolie von PowerPoint [Presentation](../) ändert. 
```cpp
// Instanziieren Sie die Presentation-Klasse, die die Präsentationsdatei darstellt
auto pres = System::MakeObject<Presentation>();

// Setze die Hintergrundfarbe der Master ISlide auf Waldgrün
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Schreibe die Präsentation auf die Festplatte
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
Das folgende Beispiel zeigt, wie man ein Folienlayout zu PowerPoint [Presentation](../) hinzufügt. 
```cpp
// Instanziieren Sie die Presentation-Klasse, die die Präsentationsdatei darstellt
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Versuchen, nach Layout-Folientyp zu suchen
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Die Situation, wenn eine Präsentation keinen bestimmten Layout-Typ enthält.
    // Die Präsentationsdatei enthält nur Layout-Typen vom Typ Blank und Custom.
    // Aber Layoutfolien mit Custom-Typen haben unterschiedliche Foliennamen,
    // wie "Title", "Title and Content" usw. Und es ist möglich, diese
    // Namen für die Auswahl von Layoutfolien zu verwenden.
    // Auch ist es möglich, das Set von Platzhalter-Formtypen zu verwenden. Zum Beispiel,
    // Titel-Folien sollten nur den Title-Platzhaltertyp haben usw.
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

// Leere Folie mit hinzugefügtem Layout einfügen
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Präsentation speichern
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMasterSlideCollection](../../imasterslidecollection/)
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)