---
title: idx_get()
second_title: Référence API Aspose.Slides pour C++
description: Obtient l'élément à l'index spécifié. Lecture seule ISummaryZoomSection.
type: docs
weight: 40
url: /fr/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) méthode

Obtient l'élément à l'index spécifié. Lecture seule [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## Remarques

L'exemple montre comment obtenir l'élément Summary Zoom [Section](../../section/) par index :
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSection](../../isummaryzoomsection/)
* Classe [SummaryZoomSectionCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)