---
title: set_Position()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta la posizione dell'etichetta dei dati. Scrivi LegendDataLabelPosition.
type: docs
weight: 79
url: /it/aspose.slides.charts/idatalabelformat/set_position/
---
## IDataLabelFormat::set_Position(LegendDataLabelPosition) metodo


Rappresenta la posizione dell'etichetta dei dati. Scrivi [LegendDataLabelPosition](../../legenddatalabelposition/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Position(LegendDataLabelPosition value)=0
```

## Osservazioni


Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una [DataLabelCollection](../../datalabelcollection/) collezione di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà Position per le nuove etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/). Rappresenta la posizione per gli oggetti [DataLabel](../../datalabel/). Impostare questa proprietà con un valore imposta anche questo valore nella proprietà Position per tutte le etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/) (ad es. \"DataLabels.DefaultDataLabelFormat.Position = val;\" causa che tutti DataLabels[i].Position è uguale a val).   


## Vedi anche

* Enum [LegendDataLabelPosition](../../legenddatalabelposition/)
* Classe [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)