---
title: pie_split_by property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by propriedade
Especifica como determinar quais pontos de dados estão no segundo segmento de pizza ou barra 
            em um gráfico de pizza-em-pizza ou barra-em-pizza.
            Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai 
            – isso é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade 
            é somente leitura.
            Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai.
            Use a propriedade ParentSeriesGroup.PieSplitBy leitura/escrita para alterar o valor.
            Somente leitura [`PieSplitType`](/slides/python-net/pt/aspose.slides.charts/piesplittype).

### Observações

1) Esta é a projeção da propriedade ParentSeriesGroup.PieSplitBy.
            2) Se o valor da propriedade for PieSplitType.Custom, então você pode definir informações de divisão 
            personalizadas com a propriedade ParentSeriesGroup.PieSplitCustomPoints.

### Definição:
```python
@property
def pie_split_by(self):
    ...
```

### Veja também
* classe [`IChartSeries`](/slides/python-net/pt/aspose.slides.charts/ichartseries)
* enumeração [`PieSplitType`](/slides/python-net/pt/aspose.slides.charts/piesplittype)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)