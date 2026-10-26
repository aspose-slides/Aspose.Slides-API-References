---
title: get_Overlap()
second_title: Riferimento API Aspose.Slides per C++
description: Specifica quanto le barre e le colonne si sovrappongono nei grafici 2-D, come percentuale (da -100% a 100%). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie genitore. È una proiezione della proprietà appropriata nel gruppo di serie genitore, quindi questa proprietà è di sola lettura. Per modificare il valore, utilizzare la proprietà di lettura/scrittura get_ParentSeriesGroup()->Overlap(). Di sola lettura int8_t.
type: docs
weight: 690
url: /it/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() metodo

Specifica quanto le barre e le colonne si sovrappongono nei grafici 2-D, come percentuale (da -100% a 100%). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie genitore. È una proiezione della proprietà appropriata nel gruppo di serie genitore, quindi questa proprietà è di sola lettura. Per modificare il valore, utilizzare la proprietà di lettura/scrittura [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/). Di sola lettura **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## Note

La sovrapposizione specifica il grado di sovrapposizione o spaziatura tra barre e colonne come percentuale della loro larghezza:
* -100%: Spaziatura massima (le barre sono completamente separate).
* 0%: Le barre sono poste una accanto all'altra senza sovrapposizione o spaziatura.
* 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa è una proiezione della proprietà [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/).

## Vedi anche

* Classe [ChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)