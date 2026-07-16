---
title: Clear()
second_title: Référence de l'API Aspose.Slides for C++
description: Supprime tous les objets SummaryZoomSection de la collection.
type: docs
weight: 105
url: /fr/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() méthode

Supprime tous les objets [SummaryZoomSection](../../summaryzoomsection/) de la collection.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Remarques

L'exemple montre comment obtenir l'élément Summary Zoom [Section](../../section/) par indice:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Voir aussi

* Classe [SummaryZoomSectionCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)