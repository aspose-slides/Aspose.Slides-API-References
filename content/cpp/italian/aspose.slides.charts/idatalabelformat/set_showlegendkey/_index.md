---
title: set_ShowLegendKey()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il comportamento di visualizzazione della chiave della legenda dell'etichetta dati di un grafico specificato. True se la chiave della legenda dell'etichetta dati è visibile. Scrivi bool.
type: docs
weight: 105
url: /it/aspose.slides.charts/idatalabelformat/set_showlegendkey/
---
## IDataLabelFormat::set_ShowLegendKey(bool) method

Rappresenta il comportamento di visualizzazione della chiave della legenda dell'etichetta dati di un grafico specificato. True se la chiave della legenda dell'etichetta dati è visibile. Scrivi **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLegendKey(bool value)=0
```

## Osservazioni

Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una raccolta [DataLabelCollection](../../datalabelcollection/) di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLegendKey per le nuove etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/). Impostare questa proprietà con valore imposta anche questo valore sulla proprietà ShowLegendKey per tutte le etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/) (i.e. \"DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;\" causa che tutti DataLabels[i].ShowLegendKey siano uguali a val).

## Vedi anche

* Classe [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)