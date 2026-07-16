---
title: GetSummarySection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Retourne l'élément Summary Zoom Section pour la section donnée.
type: docs
weight: 92
url: /fr/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) méthode


Renvoie l'élément Summary Zoom [Section](../../section/) pour la section donnée.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) pour trouver [ISection](../../isection/) |

### Valeur de retour

[ISummaryZoomSection](../../isummaryzoomsection/) ou null si la collection ne contient pas d'élément pour la section.
## Remarques



L'exemple montre comment obtenir l'élément Summary Zoom [Section](../../section/) par indice : 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSection](../../isummaryzoomsection/)
* Classe [ISection](../../isection/)
* Classe [SummaryZoomSectionCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)