---
title: get_ShowCategoryName()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nascondere. Lettura **bool**.
type: docs
weight: 144
url: /it/aspose.slides.charts/idatalabelformat/get_showcategoryname/
---
## IDataLabelFormat::get_ShowCategoryName() metodo

Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nascondere. Lettura **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowCategoryName()=0
```

## Osservazioni

Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una raccolta [DataLabelCollection](../../datalabelcollection/) di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowCategoryName per le nuove etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/). Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowCategoryName per tutte le etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/) (ad es. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" fa sì che tutti i DataLabels[i].ShowCategoryName siano uguali a val).

## Vedi anche

* Classe [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)