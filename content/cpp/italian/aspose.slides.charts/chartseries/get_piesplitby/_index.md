---
title: get_PieSplitBy()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica come determinare quali punti dati si trovano nella seconda fetta o barra in un grafico a torta di torta o a barra di torta. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie genitore – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è di sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo di serie genitore. Usa get_ParentSeriesGroup()->get(set)_PieSplitBy() proprietà di lettura/scrittura per modificare il valore. Proprietà di sola lettura PieSplitType.
type: docs
weight: 755
url: /it/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() metodo

Specifica come determinare quali punti dati si trovano nella seconda fetta o barra in un grafico a torta di torta o a barra di torta. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie genitore – è la proiezione della proprietà di gruppo appropriata. Quindi questa proprietà è di sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo di serie genitore. Usa [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() proprietà di lettura/scrittura per modificare il valore. Solo lettura [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Osservazioni

1) Questa è la proiezione della proprietà [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy().
2) Se il valore della proprietà è [PieSplitType::Custom](../../piesplittype/) allora è possibile definire informazioni di divisione personalizzate con la proprietà [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Vedi anche

* Enumerazione [PieSplitType](../../piesplittype/)
* Classe [ChartSeries](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)