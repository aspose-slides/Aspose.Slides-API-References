---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides para C++ Referência da API
description: Cria um novo quadro Summary Zoom e o adiciona ao final da coleção de formas.
type: docs
weight: 157
url: /pt/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) método

Cria um novo quadro Summary Zoom e o adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
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

Este método cria um novo Summary Zoom e coloca uma coleção de objetos nele para todas as seções desta apresentação.

Este exemplo demonstra como adicionar um objeto Summary Zoom ao final de uma coleção (assuma que há pelo menos duas seções na apresentação "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomFrame](../../isummaryzoomframe/)
* Classe [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)