---
title: AddSummaryZoomSection()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouvel objet SummaryZoomSection et l'ajoute à la collection
type: docs
weight: 53
url: /fr/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) méthode

Crée un nouvel objet Summary Zoom [Section](../../section/) et l'ajoute à la collection

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) pour un nouvel élément Summary Zoom [Section](../../section/) [ISection](../../isection/) |

### Valeur de retour

Élément [ISummaryZoomFrame](../../isummaryzoomframe/) ajouté

## Remarques

Si un élément pour cette section existe déjà dans la collection, l'élément existant est renvoyé.

L'exemple montre comment obtenir l'élément Summary Zoom [Section](../../section/) par indice :
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSection](../../isummaryzoomsection/)
* Classe [ISection](../../isection/)
* Classe [SummaryZoomSectionCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)