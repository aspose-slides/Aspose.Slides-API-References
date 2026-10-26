---
title: get_DrawingGuides()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie une collection de repères de dessin pour la diapositive de mise en page. Lecture seule IDrawingGuidesCollection
type: docs
weight: 118
url: /fr/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() méthode


Renvoie une collection de repères de dessin pour la diapositive de mise en page. Lecture seule [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## Remarques



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Ajout du nouveau guide de dessin vertical à gauche du centre de la diapositive
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Classe [LayoutSlide](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)