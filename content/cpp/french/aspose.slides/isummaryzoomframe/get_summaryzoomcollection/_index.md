---
title: get_SummaryZoomCollection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient ISummaryZoomSectionCollection pour l'objet Summary Zoom Frame.
type: docs
weight: 14
url: /fr/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() méthode


Obtient [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) pour l'objet Summary Zoom Frame.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## Remarques


L’exemple montre comment obtenir l’élément Summary Zoom [Section](../../section/) par indice : 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Classe [ISummaryZoomFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)