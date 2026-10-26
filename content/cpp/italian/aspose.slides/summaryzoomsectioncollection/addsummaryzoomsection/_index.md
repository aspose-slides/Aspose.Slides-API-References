---
title: AddSummaryZoomSection()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo oggetto Summary Zoom Section e lo aggiunge alla collezione
type: docs
weight: 53
url: /it/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) metodo

Crea un nuovo oggetto Summary Zoom [Section](../../section/) e lo aggiunge alla collezione

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) per un nuovo elemento Summary Zoom [Section](../../section/) [ISection](../../isection/) |

### Valore restituito

Elemento [ISummaryZoomFrame](../../isummaryzoomframe/) aggiunto
## Osservazioni



Se un elemento per questa sezione esiste già nella collezione, viene restituito l'elemento esistente. 


L'esempio dimostra come ottenere l'elemento Summary Zoom [Section](../../section/) per indice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)