---
title: get_PieSplitBy()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica come determinare quali punti dati si trovano nella seconda fetta o barra in un grafico a pie-of-pie o bar-of-pie. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie genitore – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è a sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo di serie genitore. Usa get_ParentSeriesGroup()->get(set)_PieSplitBy() proprietà di lettura/scrittura per modificare il valore. PieSplitType a sola lettura.
type: docs
weight: 729
url: /it/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() metodo

Specifica come determinare quali punti dati sono nella seconda fetta o barra in un grafico a pie-of-pie o bar-of-pie. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie genitore – questa è la proiezione della proprietà di gruppo appropriata. E quindi questa proprietà è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo di serie genitore. Usa [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() proprietà lettura/scrittura per modificare il valore. Sola lettura [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Note

1) Questa è la proiezione della proprietà [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Se il valore della proprietà è [PieSplitType::Custom](../../piesplittype/) allora è possibile definire informazioni di divisione personalizzate con la proprietà [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Vedi anche

* Enum [PieSplitType](../../piesplittype/)
* Classe [IChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)