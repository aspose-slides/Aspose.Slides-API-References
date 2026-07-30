---
title: Clear()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove tutti gli oggetti SummaryZoomSection dalla collezione.
type: docs
weight: 105
url: /it/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() metodo

Rimuove tutti gli oggetti [SummaryZoomSection](../../summaryzoomsection/) dalla collezione.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Osservazioni

L'esempio dimostra come ottenere l'elemento Summary Zoom [Section](../../section/) per indice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Vedi anche

* Classe [SummaryZoomSectionCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)