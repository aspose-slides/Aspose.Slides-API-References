---
title: get_Masters()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une liste de toutes les diapositives maîtresses définies dans la présentation. Lecture seule IMasterSlideCollection.
type: docs
weight: 118
url: /fr/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() méthode

Renvoie une liste de toutes les diapositives maîtresses définies dans la présentation. Lecture seule [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Remarques

Les exemples suivants montrent comment ajouter [Images](../../images/) à la diapositive maîtresse [Slides](../../) de PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
 Les exemples suivants montrent comment modifier la couleur d'arrière-plan de la diapositive maîtresse de PowerPoint [Presentation](../). 
```cpp
// Instancier la classe Presentation qui représente le fichier de présentation
auto pres = System::MakeObject<Presentation>();

// Définir la couleur d'arrière-plan du Master ISlide sur Vert forêt
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Enregistrer la présentation sur le disque
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
 Les exemples suivants montrent comment ajouter une mise en page de diapositive à PowerPoint [Presentation](../). 
```cpp
// Instancier la classe Presentation qui représente le fichier de présentation
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Essayer de rechercher par type de diapositive de mise en page
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Situation où une présentation ne contient pas certains types de mises en page.
    // Le fichier de présentation ne contient que les types de mise en page Blank et Custom.
    // Cependant, les diapositives de mise en page de type Custom ont des noms de diapositive différents,
    // comme "Title", "Title and Content", etc. Et il est possible d'utiliser ceux-ci
    // noms pour la sélection de la diapositive de mise en page.
    // Il est également possible d'utiliser l'ensemble des types de formes d'espace réservé. Par exemple,
    // La diapositive Title ne devrait avoir que le type d'espace réservé Title, etc.
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

// Ajout d'une diapositive vide avec la diapositive de mise en page ajoutée
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Enregistrer la présentation
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMasterSlideCollection](../../imasterslidecollection/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)