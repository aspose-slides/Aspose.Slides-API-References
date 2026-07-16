---
title: get_DrawingGuides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une collection de repères de dessin pour la diapositive principale du document de distribution. Lecture seule IDrawingGuidesCollection
type: docs
weight: 14
url: /fr/aspose.slides/imasterhandoutslide/get_drawingguides/
---
## IMasterHandoutSlide::get_DrawingGuides() méthode


Renvoie une collection de repères de dessin pour la diapositive principale du document de distribution. Lecture seule [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterHandoutSlide::get_DrawingGuides()=0
```

## Remarques



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Classe [IMasterHandoutSlide](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)