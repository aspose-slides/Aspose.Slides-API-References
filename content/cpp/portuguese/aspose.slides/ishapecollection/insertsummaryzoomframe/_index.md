---
title: InsertSummaryZoomFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro Summary Zoom e o insere na coleção de formas no índice especificado.
type: docs
weight: 157
url: /pt/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) method


Cria um novo quadro Summary Zoom e o insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
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

Este exemplo demonstra a criação e inserção de um objeto Summary Zoom no índice especificado de uma coleção (presuma que existam pelo menos duas seções na apresentação \"Presentation.pptx\"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomFrame](../../isummaryzoomframe/)
* Classe [IShapeCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)