---
title: GetSummarySection()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o elemento Summary Zoom Section para a seção especificada.
type: docs
weight: 92
url: /pt/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) método

Retorna o elemento Summary Zoom [Section](../../section/) para a seção fornecida.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) para encontrar [ISection](../../isection/) |

### Valor de Retorno

[ISummaryZoomSection](../../isummaryzoomsection/) ou null se a coleção não contém elemento para a seção.

## Observações

O exemplo demonstra a obtenção do elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomSection](../../isummaryzoomsection/)
* Classe [ISection](../../isection/)
* Classe [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)