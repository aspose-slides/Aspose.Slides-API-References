---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém ISummaryZoomSectionCollection para o objeto Summary Zoom Frame.
type: docs
weight: 14
url: /pt/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() método


Obtém [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) para o objeto Summary Zoom Frame.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Observações


O exemplo demonstra a obtenção do elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Classe [SummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)