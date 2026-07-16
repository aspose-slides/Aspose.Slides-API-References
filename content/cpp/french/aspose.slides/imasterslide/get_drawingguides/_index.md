---
title: get_DrawingGuides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une collection de guides de dessin pour la diapositive maître. Lecture seule IDrawingGuidesCollection
type: docs
weight: 105
url: /fr/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() méthode

Renvoie une collection de guides de dessin pour la diapositive maître. Lecture seule [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
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
* Classe [IMasterSlide](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)