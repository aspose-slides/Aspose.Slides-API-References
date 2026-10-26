---
title: get_Slides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une liste de toutes les diapositives qui sont définies dans la présentation. Lecture seule ISlideCollection.
type: docs
weight: 53
url: /fr/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() méthode

Renvoie une liste de toutes les diapositives qui sont définies dans la présentation. Lecture seule [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Remarques

 L'exemple suivant montre comment définir la couleur d'arrière-plan des diapositives de PowerPoint [Presentation](../). 
```cpp
// Instanciez la classe Presentation qui représente le fichier de présentation
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Définissez la couleur d'arrière-plan de la première ISlide en bleu
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 L'exemple suivant montre comment définir l'image d'arrière-plan des diapositives de PowerPoint [Presentation](../). 
```cpp
// Instanciez la classe Presentation qui représente le fichier de présentation
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Définissez l'arrière-plan avec une image
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Définissez l'image
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Ajoutez l'image à la collection d'images de la présentation
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Écrivez la présentation sur le disque
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 L'exemple suivant montre comment ajouter une transition de diapositive [Presentation](../). 
```cpp
// Instanciez la classe Presentation pour charger le fichier de présentation source
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Appliquez la transition de type cercle sur la diapositive 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Appliquez la transition de type peigne sur la diapositive 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Enregistrez la présentation sur le disque
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 L'exemple suivant montre comment ajouter une transition de diapositive avancée. 
```cpp
// Instanciez la classe Presentation qui représente un fichier de présentation
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Appliquez la transition de type cercle sur la diapositive 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Définissez le temps de transition à 3 secondes
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Appliquez la transition de type peigne sur la diapositive 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Définissez le temps de transition à 5 secondes
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Appliquez la transition de type zoom sur la diapositive 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Définissez le temps de transition à 7 secondes
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Enregistrez la présentation sur le disque
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlideCollection](../../islidecollection/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)