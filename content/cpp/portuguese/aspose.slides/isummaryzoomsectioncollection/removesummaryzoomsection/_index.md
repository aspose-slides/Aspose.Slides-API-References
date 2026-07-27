---
title: RemoveSummaryZoomSection()
second_title: Referência da API Aspose.Slides para C++
description: Remove o objeto Summary Zoom Section da coleção.
type: docs
weight: 40
url: /pt/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) método

Remove o objeto Summary Zoom [Section](../../section/) da coleção.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) para o qual o elemento Summary Zoom [Section](../../section/) deve ser removido [ISection](../../isection/). |

## Observações

O exemplo demonstra como obter o elemento Summary Zoom [Section](../../section/) por índice:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISection](../../isection/)
* Classe [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)