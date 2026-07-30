---
title: set_NumberFormat()
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta la stringa di formato per l'oggetto DataLabels. Scrivi System::String."
type: docs
weight: 40
url: /it/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) metodo

Rappresenta la stringa di formato per l'oggetto DataLabels. Scrivi [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Osservazioni



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



Se il genitore di questo oggetto [DataLabelFormat](../../datalabelformat/) è una collezione [DataLabelCollection](../../datalabelcollection/) di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà NumberFormat per le nuove etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/). Quando questa proprietà viene impostata con un valore, tale valore viene impostato anche per la proprietà NumberFormat di tutte le etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/) (ad esempio "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" fa sì che tutti DataLabels[i].NumberFormat siano uguali a val).

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IDataLabelFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)