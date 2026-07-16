---
title: set_Title()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le titre texte de l'objet Summary Zoom Section.
type: docs
weight: 14
url: /fr/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) méthode

Renvoie le titre texte de l'objet Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
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