---
title: Clear()
second_title: Aspose.Slides para C++ Referência da API
description: Remove todos os objetos SummaryZoomSection da coleção.
type: docs
weight: 66
url: /pt/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() método


Remove todos os objetos [SummaryZoomSection](../../summaryzoomsection/) da coleção.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## Observações


O exemplo demonstra como obter o elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Ver também

* Classe [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)