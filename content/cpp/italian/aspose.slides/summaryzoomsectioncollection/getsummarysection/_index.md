---
title: GetSummarySection()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce l'elemento Summary Zoom Section per la sezione specificata.
type: docs
weight: 92
url: /it/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) metodo


Restituisce l'elemento Summary Zoom [Section](../../section/) per la sezione specificata.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) per trovare [ISection](../../isection/) |

## Valore di ritorno

[ISummaryZoomSection](../../isummaryzoomsection/) o null se la raccolta non contiene l'elemento per la sezione.
## Osservazioni



L'esempio dimostra come ottenere l'elemento Summary Zoom [Section](../../section/) per indice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSection](../../isummaryzoomsection/)
* Classe [ISection](../../isection/)
* Classe [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)