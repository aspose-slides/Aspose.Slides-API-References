---
title: IndexOf()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um índice do objeto SummaryZoomSection especificado.
type: docs
weight: 53
url: /pt/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) método

Retorna um índice do objeto [SummaryZoomSection](../../summaryzoomsection/) especificado.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) objeto a encontrar [ISummaryZoomSection](../../isummaryzoomsection/). |

### Valor de Retorno

Índice de um objeto [SummaryZoomSection](../../summaryzoomsection/) ou -1 se o objeto [SummaryZoomSection](../../summaryzoomsection/) não for desta coleção.

## Observações

O exemplo demonstra a obtenção do elemento Summary Zoom [Section](../../section/) por índice:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSection](../../isummaryzoomsection/)
* Classe [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)