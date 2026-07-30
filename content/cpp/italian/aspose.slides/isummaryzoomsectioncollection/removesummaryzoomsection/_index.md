---
title: RemoveSummaryZoomSection()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove l'oggetto Summary Zoom Section dalla collezione.
type: docs
weight: 40
url: /it/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) metodo

Rimuovere l'oggetto Summary Zoom [Section](../../section/) dalla collezione.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) per il quale l'elemento Summary Zoom [Section](../../section/) deve essere rimosso [ISection](../../isection/). |

## Osservazioni

L'esempio dimostra come ottenere l'elemento Summary Zoom [Section](../../section/) per indice:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISection](../../isection/)
* Classe [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)