---
title: get_DrawingGuides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une collection de repères de dessin pour la diapositive maîtresse. Lecture seule IDrawingGuidesCollection
type: docs
weight: 170
url: /fr/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() méthode


Renvoie une collection de repères de dessin pour la diapositive maîtresse. Lecture seule [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## Remarques



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Ajout du nouveau guide de dessin vertical à droite du centre de la diapositive
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Classe [MasterSlide](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)