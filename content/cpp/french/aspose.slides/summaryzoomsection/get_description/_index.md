---
title: get_Description()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie la description texte de l'objet Summary Zoom Section.
type: docs
weight: 27
url: /fr/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() méthode

Renvoie la description texte de l’objet Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
```

## Remarques

Exemple:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [SummaryZoomSection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)