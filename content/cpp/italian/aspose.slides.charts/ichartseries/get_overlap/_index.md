---
title: get_Overlap()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica quanto le barre e le colonne si sovrappongono nei grafici 2-D, come percentuale (da -100% a 100%). Questa è una proprietà non solo di questa serie ma di tutte le serie del gruppo di serie genitore. È una proiezione della proprietà appropriata nel gruppo di serie genitore, quindi questa proprietà è di sola lettura. Per modificare il valore, utilizzare la proprietà di lettura/scrittura get_ParentSeriesGroup()->get(set)_Overlap(). Solo lettura int8_t.
type: docs
weight: 690
url: /it/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() metodo

Specifica quanto le barre e le colonne si sovrappongono nei grafici 2-D, come percentuale (da -100% a 100%). Questa è una proprietà non solo di questa serie ma di tutte le serie del gruppo di serie genitore. È una proiezione della proprietà appropriata nel gruppo di serie genitore, quindi questa proprietà è di sola lettura. Per cambiare il valore, utilizzare la proprietà di lettura/scrittura [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap(). Solo lettura **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Osservazioni

Overlap specifica il grado di sovrapposizione o spaziatura tra barre e colonne come percentuale della loro larghezza:* -100%: Spaziatura massima (le barre sono completamente separate).* 0%: Le barre sono posizionate una accanto all'altra senza sovrapposizione o spaziatura.* 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa è una proiezione della proprietà [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap().

## Vedi anche

* Classe [IChartSeries](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)