---
title: get_Position()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta la posizione dell'etichetta dati. Leggi LegendDataLabelPosition.
type: docs
weight: 66
url: /it/aspose.slides.charts/idatalabelformat/get_position/
---
## IDataLabelFormat::get_Position() metodo


Rappresenta la posizione dell'etichetta dati. Leggi [LegendDataLabelPosition](../../legenddatalabelposition/).

```cpp
virtual LegendDataLabelPosition Aspose::Slides::Charts::IDataLabelFormat::get_Position()=0
```

## Osservazioni


Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una raccolta [DataLabelCollection](../../datalabelcollection/) di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà Position per le nuove etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/). Rappresenta la posizione per gli oggetti [DataLabel](../../datalabel/). Impostando questa proprietà con un valore, si imposta anche questo valore alla proprietà Position per tutte le etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/) (ad es. "DataLabels.DefaultDataLabelFormat.Position = val;" causa che tutti DataLabels[i].Position siano uguali a val).



## Vedi anche

* Enum [LegendDataLabelPosition](../../legenddatalabelposition/)
* Classe [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)