---
title: get_Separator()
second_title: Riferimento API di Aspose.Slides per C++
description: "Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dei dati su un grafico. Leggi System::String."
type: docs
weight: 326
url: /it/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() metodo

Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dei dati su un grafico. Leggi [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## Osservazioni

Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una [DataLabelCollection](../../datalabelcollection/) raccolta di etichette dei dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà Separator per le nuove etichette dei dati nella raccolta [DataLabelCollection](../../datalabelcollection/). Impostare questa proprietà con valore imposta anche questo valore alla proprietà Separator per tutte le etichette dei dati nella raccolta [DataLabelCollection](../../datalabelcollection/) (ad esempio "DataLabels.DefaultDataLabelFormat.Separator = val;" fa sì che tutti DataLabels[i].Separator siano uguali a val).

## Vedere anche

* Classe [String](../../../system/string/)
* Classe [IDataLabelFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)