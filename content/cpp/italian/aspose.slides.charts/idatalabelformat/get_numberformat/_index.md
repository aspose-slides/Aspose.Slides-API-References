---
title: get_NumberFormat()
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta la stringa di formato per l'oggetto DataLabels. Leggi System::String."
type: docs
weight: 27
url: /it/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() metodo


Rappresenta la stringa di formato per l'oggetto DataLabels. Leggi [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## Osservazioni



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una raccolta [DataLabelCollection](../../datalabelcollection/) di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà NumberFormat per le nuove etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/). Quando questa proprietà viene impostata con un valore, tale valore viene impostato anche per la proprietà NumberFormat di tutte le etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/) (i.e. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" fa sì che tutti i DataLabels[i].NumberFormat siano uguali a val). 

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IDataLabelFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)