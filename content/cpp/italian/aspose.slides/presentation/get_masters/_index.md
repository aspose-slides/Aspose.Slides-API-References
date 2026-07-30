---
title: get_Masters()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un elenco di tutte le diapositive master definite nella presentazione. Sola lettura IMasterSlideCollection.
type: docs
weight: 118
url: /it/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() metodo


Restituisce un elenco di tutte le diapositive master definite nella presentazione. Solo lettura [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Osservazioni


I seguenti esempi mostrano come aggiungere [Images](../../images/) al Master [Slides](../../) di PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
I seguenti esempi mostrano come cambiare il colore di sfondo della diapositiva master di PowerPoint [Presentation](../). 
```cpp
// Istanziare la classe Presentation che rappresenta il file di presentazione
auto pres = System::MakeObject<Presentation>();

// Impostare il colore di sfondo del Master ISlide a Verde foresta
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Scrivere la presentazione su disco
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
I seguenti esempi mostrano come aggiungere il layout delle diapositive a PowerPoint [Presentation](../). 
```cpp
// Istanziare la classe Presentation che rappresenta il file di presentazione
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Provare a cercare per tipo di diapositiva layout
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Situazione in cui una presentazione non contiene alcuni tipi di layout.
    // Il file di presentazione contiene solo tipi di layout Blank e Custom.
    // Ma le diapositive layout con tipi Custom hanno nomi di diapositiva diversi,
    // come "Title", "Title and Content", ecc. È possibile utilizzare questi
    // nomi per la selezione della diapositiva layout.
    // È anche possibile utilizzare l'insieme dei tipi di forma placeholder. Per esempio,
    // la diapositiva Title dovrebbe avere solo il tipo di placeholder Title, ecc.
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

// Aggiungere una diapositiva vuota con la diapositiva layout aggiunta
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Salvare la presentazione
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMasterSlideCollection](../../imasterslidecollection/)
* classe [Presentation](../)
* namespace [Aspose::Slides](../../)
* libreria [Aspose.Slides](../../../)