---
title: series_groups property
second_title: Aspose.Slides para Python via .NET API Reference
description: 
type: docs
url: /pt/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups propriedade
Obtém os grupos de séries.
Somente leitura [`IChartSeriesGroupCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroupcollection).

### Observações

1) Cada grupo de séries contém séries com tipos combináveis. Grupos de tipos de séries combináveis definidos e descritos com o enum CombinableSeriesTypesGroup. Além disso, cada grupo de séries contém séries que são plotadas nos eixos primários ou nos eixos secundários (não ambos os casos em um mesmo grupo). Portanto, o princípio do agrupamento de séries é um agrupamento pelos grupos de tipo mencionados acima e pelo tipo de plotagem primário/segundário.

2) O grupo de séries contém algumas propriedades de séries que são comuns a cada série no grupo ("propriedades do grupo de séries"). "Propriedades do grupo de séries" na classe ChartSeriesGroup é leitura/gravação. Cada uma das "propriedades do grupo de séries" pode ter uma projeção somente leitura na classe ChartSeries.

### Definição:
```python
@property
def series_groups(self):
    ...
```

### Ver também
* classe [`ChartData`](/slides/python-net/pt/aspose.slides.charts/chartdata)
* classe [`IChartSeriesGroupCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroupcollection)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)