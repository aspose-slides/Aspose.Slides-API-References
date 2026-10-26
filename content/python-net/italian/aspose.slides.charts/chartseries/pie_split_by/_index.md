---
title: pie_split_by property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by proprietà
Specifica come determinare quali punti dati sono nella seconda torta o barra su un grafico a pie-of-pie o bar-of-pie. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre - questa è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è di sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.PieSplitBy di lettura/scrittura per cambiare il valore. Di sola lettura [`PieSplitType`](/slides/python-net/it/aspose.slides.charts/piesplittype).

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
* class [`ChartSeries`](/slides/python-net/it/aspose.slides.charts/chartseries)
* enumeration [`PieSplitType`](/slides/python-net/it/aspose.slides.charts/piesplittype)
* module [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)