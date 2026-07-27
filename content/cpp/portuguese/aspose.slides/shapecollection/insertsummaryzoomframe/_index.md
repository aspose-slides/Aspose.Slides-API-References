---
title: InsertSummaryZoomFrame()
second_title: Referência da API Aspose.Slides for C++
description: Cria um novo quadro Summary Zoom e o insere na coleção de formas no índice especificado.
type: docs
weight: 170
url: /pt/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) método

Cria um novo quadro Summary Zoom e o insere na coleção de formas no índice especificado.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o quadro Summary Zoom. |
| x | **float** | A coordenada x do novo quadro Summary Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro Summary Zoom, em pontos. |
| width | **float** | A largura do novo quadro Summary Zoom, em pontos. |
| height | **float** | A altura do novo quadro Summary Zoom, em pontos. |

### Valor de Retorno

O [ISummaryZoomFrame](../../isummaryzoomframe/) recém-criado.

## Observações

Este método cria um quadro Summary Zoom que agrega links de resumo para todas as seções da apresentação. 

Este exemplo demonstra a criação e inserção de um objeto Summary Zoom no índice especificado de uma coleção (suponha que existam pelo menos duas seções na apresentação "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomFrame](../../isummaryzoomframe/)
* Classe [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)