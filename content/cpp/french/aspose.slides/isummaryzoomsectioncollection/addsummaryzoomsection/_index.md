---
title: AddSummaryZoomSection()
second_title: Référence de l'API Aspose.Slides for C++
description: Crée un nouvel objet Summary Zoom Section et l'ajoute à la collection
type: docs
weight: 14
url: /fr/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) méthode

Crée un nouvel objet Summary Zoom [Section](../../section/) et l'ajoute à la collection

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) pour un nouveau Summary Zoom [Section](../../section/) élément [ISection](../../isection/) |

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
* Classe [ISummaryZoomSectionCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)