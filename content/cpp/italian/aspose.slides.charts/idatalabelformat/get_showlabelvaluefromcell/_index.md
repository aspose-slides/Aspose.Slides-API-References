---
title: get_ShowLabelValueFromCell()
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. True visualizza il valore della cella. False per nasconderlo. Leggi bool.
type: docs
weight: 300
url: /it/aspose.slides.charts/idatalabelformat/get_showlabelvaluefromcell/
---
## IDataLabelFormat::get_ShowLabelValueFromCell() metodo


Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. True visualizza il valore della cella. False per nasconderlo. Lettura **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelValueFromCell()=0
```

## Osservazioni


Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una raccolta [DataLabelCollection](../../datalabelcollection/) di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelValueFromCell per le nuove etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/). Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowLabelValueFromCell per tutte le etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/) (ad esempio \"DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;\" causa che tutti DataLabels[i].ShowLabelValueFromCell siano uguali a val). 
## Vedi anche

* Classe [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)