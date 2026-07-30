---
title: get_ShowLegendKey()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il comportamento di visualizzazione della chiave della leggenda dell'etichetta dati di un grafico specificato. True se la chiave della leggenda dell'etichetta dati è visibile. Lettura bool.
type: docs
weight: 92
url: /it/aspose.slides.charts/idatalabelformat/get_showlegendkey/
---
## IDataLabelFormat::get_ShowLegendKey() metodo

Rappresenta il comportamento di visualizzazione della chiave della leggenda dell’etichetta dati di un grafico specificato. True se la chiave della leggenda dell’etichetta dati è visibile. Lettura **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLegendKey()=0
```

## Osservazioni

Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una raccolta [DataLabelCollection](../../datalabelcollection/) di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLegendKey per le nuove etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/). Impostare questa proprietà con valore imposta anche questo valore sulla proprietà ShowLegendKey per tutte le etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/) (ad esempio \"DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;\" causa che tutti DataLabels[i].ShowLegendKey siano uguali a val).

## Vedi anche

* Classe [IDataLabelFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)