---
title: IChartSeriesGroupCollection class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection classe

Representa a coleção de grupos de séries combináveis.

O tipo IChartSeriesGroupCollection expõe os seguintes membros:

Obtém o grupo de séries por índice.

## Indexer

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |


### Observações

1) Cada grupo de séries contém séries com tipos combináveis. Grupos de 
            tipos de séries combináveis são definidos e descritos com o enum 
            CombinableSeriesTypesGroup. 
            Também cada grupo de séries contém séries que são plotadas tanto 
            em eixos primários quanto em eixos secundários (não ambos os casos em um mesmo grupo). 
            Portanto, o princípio do agrupamento de séries é um agrupamento pelos tipos de grupos mencionados 
            acima e pelo tipo de plotagem primário/secundário.

2) O grupo de séries contém algumas propriedades de séries que são comuns a 
            cada série no grupo (“propriedades do grupo de séries”). 
            “Propriedades do grupo de séries” na classe ChartSeriesGroup são leitura/gravação. 
            Cada “propriedade do grupo de séries” pode ter uma projeção somente leitura na classe ChartSeries.

### Veja também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)