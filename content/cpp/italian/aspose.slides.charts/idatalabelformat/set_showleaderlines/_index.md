---
title: set_ShowLeaderLines()
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta il comportamento di visualizzazione delle linee guida delle etichette dati di un grafico specificato. True visualizza le linee guida. False per nasconderle. Scrivi bool.
type: docs
weight: 261
url: /it/aspose.slides.charts/idatalabelformat/set_showleaderlines/
---
## IDataLabelFormat::set_ShowLeaderLines(bool) metodo

Rappresenta il comportamento di visualizzazione delle linee guida delle etichette dati di un grafico specificato. True visualizza le linee guida. False per nasconderle. Scrivi **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLeaderLines(bool value)=0
```

## Osservazioni

Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una collezione [DataLabelCollection](../../datalabelcollection/) di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLeaderLines per le nuove etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/). Impostare questa proprietà con un valore imposta anche questo valore sulla proprietà ShowLeaderLines per tutte le etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/) (ad esempio "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" provoca che tutti DataLabels[i].ShowLeaderLines siano uguali a val).

## Vedi anche

* Classe [IDataLabelFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)