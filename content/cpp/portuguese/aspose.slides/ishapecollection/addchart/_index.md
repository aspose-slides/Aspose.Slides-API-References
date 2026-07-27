---
title: AddChart()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações e o adiciona ao final da coleção de formas.
type: docs
weight: 27
url: /pt/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) método

Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações e o adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | O tipo de gráfico a ser adicionado. |
| x | **float** | A coordenada x do novo gráfico, em pontos. |
| y | **float** | A coordenada y do novo gráfico, em pontos. |
| width | **float** | A largura do gráfico, em pontos. |
| height | **float** | A altura do gráfico, em pontos. |

### Valor de Retorno

O [Charts::IChart](../../../aspose.slides.charts/ichart/) recém-criado.

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) método

Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações e o adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | O tipo de gráfico a ser adicionado. |
| x | **float** | A coordenada x do novo gráfico, em pontos. |
| y | **float** | A coordenada y do novo gráfico, em pontos. |
| width | **float** | A largura do gráfico, em pontos. |
| height | **float** | A altura do gráfico, em pontos. |
| initWithSample | **bool** | Verdadeiro para inicializar o novo gráfico com dados de série de exemplo e configurações; falso para criar o gráfico sem séries e apenas com configurações mínimas, o que torna a criação mais rápida. |

### Valor de Retorno

O [Charts::IChart](../../../aspose.slides.charts/ichart/) recém-criado.

## Veja Também

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChart](../../../aspose.slides.charts/ichart/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)