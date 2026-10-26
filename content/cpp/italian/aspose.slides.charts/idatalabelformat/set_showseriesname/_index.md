---
title: set_ShowSeriesName()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta un valore Booleano per indicare il comportamento di visualizzazione del nome della serie per le etichette dati in un grafico. True per mostrare il nome della serie. False per nascondere. Scrivi bool.
type: docs
weight: 183
url: /it/aspose.slides.charts/idatalabelformat/set_showseriesname/
---
## IDataLabelFormat::set_ShowSeriesName(bool) metodo

Imposta un valore Booleano per indicare il comportamento di visualizzazione del nome della serie per le etichette dati in un grafico. True per mostrare il nome della serie. False per nascondere. Scrivi **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowSeriesName(bool value)=0
```

## Osservazioni

Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una collezione [DataLabelCollection](../../datalabelcollection/) di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowSeriesName per le nuove etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/). Impostare questa proprietà con un valore imposta anche tale valore nella proprietà ShowSeriesName per tutte le etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/) (ad esempio "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" fa sì che tutti DataLabels[i].ShowSeriesName sia uguale a val).

## Vedi anche

* Classe [IDataLabelFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)