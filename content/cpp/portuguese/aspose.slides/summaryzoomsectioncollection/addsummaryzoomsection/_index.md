---
title: AddSummaryZoomSection()
second_title: Aspose.Slides para C++ Referência da API
description: Cria um novo objeto Summary Zoom Section e o adiciona à coleção
type: docs
weight: 53
url: /pt/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) método

Cria um novo objeto Summary Zoom [Section](../../section/) e o adiciona à coleção

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) para um novo elemento Summary Zoom [Section](../../section/) [ISection](../../isection/) |

### Valor de Retorno

Elemento [ISummaryZoomFrame](../../isummaryzoomframe/) adicionado

## Observações

Se já existir um elemento para esta seção na coleção, o elemento existente será retornado.

O exemplo demonstra a obtenção do elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)