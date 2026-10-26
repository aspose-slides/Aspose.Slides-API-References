---
title: IndexOf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un indice de l'objet SummaryZoomSection spécifié.
type: docs
weight: 53
url: /fr/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) méthode

Renvoie un indice de l'objet [SummaryZoomSection](../../summaryzoomsection/) spécifié.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) objet à trouver [ISummaryZoomSection](../../isummaryzoomsection/). |

### Valeur de retour

Indice d'un objet [SummaryZoomSection](../../summaryzoomsection/) ou -1 si l'objet [SummaryZoomSection](../../summaryzoomsection/) ne provient pas de cette collection.
## Remarques



L'exemple montre comment obtenir l'élément Summary Zoom [Section](../../section/) par indice:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSection](../../isummaryzoomsection/)
* Classe [ISummaryZoomSectionCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)