---
title: set_Description()
second_title: Référence API Aspose.Slides pour C++
description: Retourne la description texte de l’objet Summary Zoom Section.
type: docs
weight: 40
url: /fr/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) méthode

Retourne la description texte de l’objet Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
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