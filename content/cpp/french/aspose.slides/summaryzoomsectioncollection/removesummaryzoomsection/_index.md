---
title: RemoveSummaryZoomSection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime l'objet Summary Zoom Section de la collection.
type: docs
weight: 79
url: /fr/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) méthode

Supprime l'objet Summary Zoom [Section](../../section/) de la collection.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) pour laquelle l'élément Summary Zoom [Section](../../section/) doit être supprimé [ISection](../../isection/). |

## Remarques

L'exemple montre comment obtenir l'élément Summary Zoom [Section](../../section/) par indice :

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)