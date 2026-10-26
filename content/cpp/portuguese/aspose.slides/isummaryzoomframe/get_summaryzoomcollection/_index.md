---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides para Referência da API C++
description: Obtém ISummaryZoomSectionCollection para o objeto Summary Zoom Frame.
type: docs
weight: 14
url: /pt/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() método

Obtém [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) para o objeto Summary Zoom Frame.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## Observações

O exemplo demonstra a obtenção do elemento Summary Zoom [Section](../../section/) por índice:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Classe [ISummaryZoomFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)