---
title: AddSummaryZoomFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro Summary Zoom e o adiciona ao final da coleção de shapes.
type: docs
weight: 144
url: /pt/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) método

Cria um novo quadro Summary Zoom e o adiciona ao final da coleção de shapes.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro Summary Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro Summary Zoom, em pontos. |
| width | **float** | A largura do novo quadro Summary Zoom, em pontos. |
| height | **float** | A altura do novo quadro Summary Zoom, em pontos. |

### Valor de Retorno

O [ISummaryZoomFrame](../../isummaryzoomframe/) recém-criado.

## Observações

Este método cria um quadro Summary Zoom que agrega links de resumo para todas as seções da apresentação. 

Este exemplo demonstra como adicionar um objeto Summary Zoom ao final de uma coleção (suponha que existam ao menos duas seções na apresentação "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomFrame](../../isummaryzoomframe/)
* Classe [IShapeCollection](../)
* namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)