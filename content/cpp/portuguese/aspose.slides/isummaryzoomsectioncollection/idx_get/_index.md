---
title: idx_get()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o elemento no índice especificado. Somente leitura ISummaryZoomSection.
type: docs
weight: 1
url: /pt/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) método

Obtém o elemento no índice especificado. Somente leitura [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## Observações

O exemplo demonstra como obter o elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)