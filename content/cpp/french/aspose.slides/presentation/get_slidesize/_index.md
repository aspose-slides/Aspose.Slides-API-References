---
title: get_SlideSize()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie l'objet de taille de diapositive. Lecture seule ISlideSize.
type: docs
weight: 79
url: /fr/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() méthode


Renvoie l'objet de taille de diapositive. Lecture seule [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Remarques


L'exemple suivant montre comment modifier la taille de la diapositive dans un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 L'exemple suivant montre comment définir la taille de la diapositive en fonction du redimensionnement du contenu pour un PowerPoint [Presentation](../). 
```cpp
// Instanciez un objet Presentation qui représente un fichier de présentation
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Définissez la taille de la diapositive des présentations générées à celle de la source
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// La méthode SetSize est utilisée pour définir la taille de la diapositive avec mise à l'échelle du contenu afin d'assurer l'ajustement
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// La méthode SetSize est utilisée pour définir la taille de la diapositive en maximisant la taille du contenu
// Enregistrez la présentation sur le disque
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 L'exemple suivant montre comment spécifier des tailles de diapositive personnalisées dans un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// Taille du papier A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlideSize](../../islidesize/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)