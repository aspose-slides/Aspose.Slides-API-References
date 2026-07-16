---
title: get_Title()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie le titre texte de l'objet Summary Zoom Section.
type: docs
weight: 1
url: /fr/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() méthode

Renvoie le titre texte de l'objet Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
```

## Remarques


Exemple :
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [SummaryZoomSection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)