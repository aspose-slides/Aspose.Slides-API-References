---
title: InsertChart()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado.
type: docs
weight: 92
url: /pt/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) método

Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | O tipo de gráfico a ser criado. |
| x | **float** | A coordenada x do novo gráfico, em pontos. |
| y | **float** | A coordenada y do novo gráfico, em pontos. |
| width | **float** | A largura do novo gráfico, em pontos. |
| height | **float** | A altura do novo gráfico, em pontos. |
| index | **int32_t** | O índice baseado em zero no qual inserir o novo gráfico na coleção de formas. |

### Valor de retorno

O [Charts::IChart](../../../aspose.slides.charts/ichart/) recém-criado.

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) método

Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | O tipo de gráfico a ser criado. |
| x | **float** | A coordenada x do novo gráfico, em pontos. |
| y | **float** | A coordenada y do novo gráfico, em pontos. |
| width | **float** | A largura do novo gráfico, em pontos. |
| height | **float** | A altura do novo gráfico, em pontos. |
| index | **int32_t** | O índice baseado em zero no qual inserir o novo gráfico na coleção de formas. |
| initWithSample | **bool** | Verdadeiro para inicializar o novo gráfico com dados de série de exemplo e configurações; falso para criar o gráfico sem séries e apenas com configurações mínimas, o que torna a criação mais rápida. |

### Valor de retorno

O [Charts::IChart](../../../aspose.slides.charts/ichart/) recém-criado.

## Veja também

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChart](../../../aspose.slides.charts/ichart/)
* Classe [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)