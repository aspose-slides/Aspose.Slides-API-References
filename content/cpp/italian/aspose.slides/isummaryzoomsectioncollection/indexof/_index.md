---
title: IndexOf()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un indice dell'oggetto SummaryZoomSection specificato.
type: docs
weight: 53
url: /it/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metodo

Restituisce un indice dell'oggetto [SummaryZoomSection](../../summaryzoomsection/) specificato.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | Oggetto [SummaryZoomSection](../../summaryzoomsection/) da trovare [ISummaryZoomSection](../../isummaryzoomsection/). |

### Valore di ritorno

Indice di un oggetto [SummaryZoomSection](../../summaryzoomsection/) o -1 se l'oggetto [SummaryZoomSection](../../summaryzoomsection/) non proviene da questa collezione.

## Osservazioni

L'esempio mostra come ottenere l'elemento Summary Zoom [Section](../../section/) tramite indice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSection](../../isummaryzoomsection/)
* Classe [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)