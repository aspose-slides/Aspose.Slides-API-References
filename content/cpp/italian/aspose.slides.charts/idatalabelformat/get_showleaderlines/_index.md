---
title: get_ShowLeaderLines()
second_title: Aspose.Slides per C++ Riferimento API
description: Rappresenta il comportamento di visualizzazione delle linee guida delle etichette dati di un grafico specificato. True visualizza le linee guida. False per nasconderle. Leggi bool.
type: docs
weight: 248
url: /it/aspose.slides.charts/idatalabelformat/get_showleaderlines/
---
## IDataLabelFormat::get_ShowLeaderLines() metodo

Rappresenta il comportamento di visualizzazione delle linee guida delle etichette dati di un grafico specificato. True visualizza le linee guida. False per nasconderle. Leggi **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLeaderLines()=0
```

## Osservazioni

Se il genitore di questo [DataLabelFormat](../../datalabelformat/) è una collezione [DataLabelCollection](../../datalabelcollection/) di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLeaderLines per le nuove etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/). Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowLeaderLines per tutte le etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/) (ad esempio "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" causa che tutti DataLabels[i].ShowLeaderLines sia uguale a val).

## Vedi anche

* Classe [IDataLabelFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)