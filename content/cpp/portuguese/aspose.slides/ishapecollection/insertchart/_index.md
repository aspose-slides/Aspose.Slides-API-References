---
title: InsertChart()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo chart, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado.
type: docs
weight: 53
url: /pt/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) método

Cria um novo chart, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | O tipo de chart a ser criado. |
| x | **float** | A coordenada x do novo chart, em pontos. |
| y | **float** | A coordenada y do novo chart, em pontos. |
| width | **float** | A largura do novo chart, em pontos. |
| height | **float** | A altura do novo chart, em pontos. |
| index | **int32_t** | O índice baseado em zero no qual inserir o novo chart na coleção de formas. |

### Valor de retorno

O [Charts::IChart](../../../aspose.slides.charts/ichart/) recém-criado.

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) método

Cria um novo chart, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | O tipo de chart a ser criado. |
| x | **float** | A coordenada x do novo chart, em pontos. |
| y | **float** | A coordenada y do novo chart, em pontos. |
| width | **float** | A largura do novo chart, em pontos. |
| height | **float** | A altura do novo chart, em pontos. |
| index | **int32_t** | O índice baseado em zero no qual inserir o novo chart na coleção de formas. |
| initWithSample | **bool** | Verdadeiro para inicializar o novo chart com dados de série de exemplo e configurações; falso para criar o chart sem séries e somente com configurações mínimas, o que torna a criação mais rápida. |

### Valor de retorno

O [Charts::IChart](../../../aspose.slides.charts/ichart/) recém-criado.

## Veja Também

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChart](../../../aspose.slides.charts/ichart/)
* Classe [IShapeCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)