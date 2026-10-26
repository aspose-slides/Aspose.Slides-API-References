---
title: Clear()
second_title: Referência da API Aspose.Slides para C++
description: Remove todos os objetos SummaryZoomSection da coleção.
type: docs
weight: 105
url: /pt/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() método


Remove todos os objetos [SummaryZoomSection](../../summaryzoomsection/) da coleção.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Observações


O exemplo demonstra a obtenção do elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Ver também

* Classe [SummaryZoomSectionCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)