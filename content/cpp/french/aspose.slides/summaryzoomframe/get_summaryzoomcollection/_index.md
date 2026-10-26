---
title: get_SummaryZoomCollection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient ISummaryZoomSectionCollection pour l'objet Summary Zoom Frame.
type: docs
weight: 14
url: /fr/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() méthode


Obtient [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) pour l'objet Summary Zoom Frame.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Remarques


L'exemple montre comment obtenir l'élément Summary Zoom [Section](../../section/) par index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Classe [SummaryZoomFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)