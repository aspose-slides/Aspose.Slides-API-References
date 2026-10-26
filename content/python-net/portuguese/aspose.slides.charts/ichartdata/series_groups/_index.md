---
title: series_groups property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups propriedade
Obtém os grupos de séries.
            Somente leitura [`IChartSeriesGroupCollection`](/slides/python-net/pt/aspose.slides.charts/ichartseriesgroupcollection).

### Observações

1) Cada grupo de séries contém séries com tipos combináveis. Grupos de 
            tipos de séries combináveis definidos e descritos com CombinableSeriesTypesGroup 
            enum.
            Além disso, cada grupo de séries contém séries que são plotadas se 
            em eixos principais ou em eixos secundários (não ambos os casos em um único grupo).
            Portanto, o princípio de agrupamento de séries é um agrupamento pelos grupos de tipos mencionados 
            acima e pelo tipo de plotagem principal/secundário.
            
            2) Grupo de séries contém algumas propriedades de séries que são comuns a 
            cada série no grupo ("propriedades do grupo de séries").
            "Propriedades do grupo de séries" na classe ChartSeriesGroup é leitura/gravação.
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