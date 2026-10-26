---
title: Remove()
second_title: Referência da API Aspose.Slides para C++
description: Remove o item da coleção.
type: docs
weight: 79
url: /pt/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) método


Remove o item da coleção.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Ponto de dados a ser removido. |

### Valor de Retorno

true se o item for removido com sucesso; caso contrário, false. Este método também retorna false se o item não for encontrado em [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) método


Remove o item da coleção pelo seu índice na coleção de pontos da série pai.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Índice do ponto de dados na coleção de pontos da série pai. |

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataPoint](../../ichartdatapoint/)
* Classe [PieSplitCustomPointCollection](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)