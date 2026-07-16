---
title: set_Description()
second_title: Référence de l'API Aspose.Slides pour C++
description: Retourne la description texte de l'objet Summary Zoom Section.
type: docs
weight: 40
url: /fr/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) method


Retourne la description texte de l'objet Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
```

## Remarques


Exemple :
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Voir aussi

* classe [String](../../../system/string/)
* classe [ISummaryZoomSection](../)
* espace de noms [Aspose::Slides](../../)
* bibliothèque [Aspose.Slides](../../../)