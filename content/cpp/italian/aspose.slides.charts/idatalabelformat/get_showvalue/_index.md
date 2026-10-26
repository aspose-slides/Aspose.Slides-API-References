---
title: get_ShowValue()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False lo nasconde. Leggi bool.
type: docs
weight: 118
url: /it/aspose.slides.charts/idatalabelformat/get_showvalue/
---
## IDataLabelFormat::get_ShowValue() metodo


Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False lo nasconde. Leggi **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowValue()=0
```

## Osservazioni


Se il genitore di questo [DataLabelFormat](../../datalabelformat/) oggetto è una collezione [DataLabelCollection](../../datalabelcollection/) di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà ShowValue per le nuove etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/). Impostare questa proprietà con valore imposta anche questo valore alla proprietà ShowValue per tutte le etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/) (ad esempio \"DataLabels.DefaultDataLabelFormat.ShowValue = val;\" causa che tutti DataLabels[i].ShowValue siano uguali a val). 



## Vedi anche

* Classe [IDataLabelFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)