---
title: get_ShowBubbleSize()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il comportamento di visualizzazione del valore della dimensione del cerchio dell'etichetta dati di un grafico specificato. True visualizza il valore della dimensione del cerchio. False per nascondere. Leggi bool.
type: docs
weight: 222
url: /it/aspose.slides.charts/idatalabelformat/get_showbubblesize/
---
## IDataLabelFormat::get_ShowBubbleSize() metodo


Rappresenta il comportamento di visualizzazione del valore della dimensione del cerchio dell'etichetta dati di un grafico specificato. True visualizza il valore della dimensione del cerchio. False per nascondere. Leggi **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowBubbleSize()=0
```

## Osservazioni


Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una collezione [DataLabelCollection](../../datalabelcollection/) di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà ShowBubbleSize per le nuove etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/). Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowBubbleSize per tutte le etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/) (ad es. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" causa che tutti DataLabels[i].ShowBubbleSize sia uguale a val).

## Vedi anche

* Classe [IDataLabelFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)