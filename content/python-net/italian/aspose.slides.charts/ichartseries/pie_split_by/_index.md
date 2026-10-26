---
title: pie_split_by property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by proprietà
Specifica come determinare quali punti dati si trovano nella seconda torta o barra su un grafico a pie-of-pie o bar-of-pie.  
Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è di sola lettura.  
Usa la proprietà ParentSeriesGroup per accedere al gruppo di serie padre.  
Usa la proprietà ParentSeriesGroup.PieSplitBy di lettura/scrittura per modificare il valore.  
Solo lettura [`PieSplitType`](/slides/python-net/it/aspose.slides.charts/piesplittype).

### Osservazioni

1) Questa è la proiezione della proprietà ParentSeriesGroup.PieSplitBy.  
2) Se il valore della proprietà è PieSplitType.Custom, è possibile definire informazioni di suddivisione personalizzate con la proprietà ParentSeriesGroup.PieSplitCustomPoints.

### Definizione:
```python
@property
def pie_split_by(self):
    ...
```

### Vedi anche
* classe [`IChartSeries`](/slides/python-net/it/aspose.slides.charts/ichartseries)
* enumerazione [`PieSplitType`](/slides/python-net/it/aspose.slides.charts/piesplittype)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)