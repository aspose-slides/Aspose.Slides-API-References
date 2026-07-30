---
title: IndexOf()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce l'indice dell'oggetto SummaryZoomSection specificato.
type: docs
weight: 66
url: /it/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metodo


Restituisce un indice dell'oggetto [SummaryZoomSection](../../summaryzoomsection/) specificato.

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) oggetto da trovare [ISummaryZoomSection](../../isummaryzoomsection/). |

### Valore di ritorno

Indice di un oggetto [SummaryZoomSection](../../summaryzoomsection/) o -1 se l'oggetto [SummaryZoomSection](../../summaryzoomsection/) non proviene da questa collezione.
## Note



L'esempio dimostra come ottenere l'elemento Summary Zoom [Section](../../section/) tramite indice: 
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
* Classe [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)