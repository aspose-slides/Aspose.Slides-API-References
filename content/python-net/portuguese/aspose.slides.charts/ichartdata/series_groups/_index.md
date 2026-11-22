---
title: series_groups property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups propriedade
Obtém os grupos de séries.
            Somente leitura [`IChartSeriesGroupCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroupcollection).

### Observações

1) Cada grupo de séries contém séries com tipos combináveis. Grupos de 
            tipos de séries combináveis são definidos e descritos com o enum CombinableSeriesTypesGroup.
            Além disso, cada grupo de séries contém séries que são plotadas nos 
            eixos primários ou nos eixos secundários (não ambos os casos em um mesmo grupo).
            Portanto, o princípio de agrupamento de séries é um agrupamento pelos grupos de tipos mencionados 
            acima e pelo tipo de plotagem primária/secundária.

2) Um grupo de séries contém algumas propriedades de série que são comuns a 
            cada série no grupo ("propriedades do grupo de séries").
            As "propriedades do grupo de séries" na classe ChartSeriesGroup são leitura/gravação.
            Cada uma das "propriedades do grupo de séries" pode ter uma projeção somente leitura na classe ChartSeries.

### Definição:
```python
@property
def series_groups(self):
    ...
```

### Ver também
* classe [`IChartData`](/slides/python-net/pt/aspose.slides.charts/ichartdata)
* classe [`IChartSeriesGroupCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroupcollection)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)