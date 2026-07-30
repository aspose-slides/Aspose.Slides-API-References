---
title: get_SummaryZoomCollection()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene ISummaryZoomSectionCollection per l'oggetto Summary Zoom Frame.
type: docs
weight: 14
url: /it/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() metodo

Ottiene [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) per l'oggetto Summary Zoom Frame.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Note

L'esempio dimostra come ottenere l'elemento Summary Zoom [Section](../../section/) per indice:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Classe [SummaryZoomFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)