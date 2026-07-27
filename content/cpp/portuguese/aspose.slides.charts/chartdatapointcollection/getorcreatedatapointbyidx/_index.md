---
title: GetOrCreateDataPointByIdx()
second_title: Referência da API Aspose.Slides para C++
description: "Se a coleção já contém um ponto de dados com o índice index, então retorna esse ponto de dados. Se a coleção não contém um ponto de dados com o índice index ==N (quando o número de pontos de dados nesta coleção é menor ou igual a N), então adiciona pontos de dados deficientes e retorna o último (que tem o índice solicitado). Por exemplo, os índices da coleção são {0, 1, 2}, e o índice solicitado é 5. Então o método adiciona pontos de dados deficientes: {0, 1, 2, 3, 4, 5}. E retorna o ponto de dados com o índice 5."
type: docs
weight: 170
url: /pt/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) método


Se a coleção já contém um ponto de dados com o índice *index* então retorna esse ponto de dados. Se a coleção não contém um ponto de dados com o índice *index* ==N (quando o número de pontos de dados nesta coleção é menor ou igual a N) então adiciona pontos de dados deficientes e retorna o último (que tem o índice solicitado). Por exemplo, os índices da coleção são {0, 1, 2}, e o índice solicitado é 5. Então o método adiciona pontos de dados deficientes: {0, 1, 2, 3, 4, 5}. E retorna o ponto de dados com o índice 5.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **uint32_t** | Índice. |

### Valor de retorno

Retorna o ponto de dados com o índice solicitado.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataPoint](../../ichartdatapoint/)
* Classe [ChartDataPointCollection](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)