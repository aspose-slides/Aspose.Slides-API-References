---
title: set_NumberFormat()
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta la stringa di formato per l'oggetto DataLabels. Scrivi System::String."
type: docs
weight: 40
url: /it/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) metodo


Rappresenta la stringa di formato per l'oggetto DataLabels. Scrivi [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Note



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



Se il genitore di questo oggetto [DataLabelFormat](../) è una raccolta [DataLabelCollection](../../datalabelcollection/) di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà NumberFormat per le nuove etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/). Quando questa proprietà viene impostata con un valore, quel valore viene anche impostato per la proprietà NumberFormat di tutte le etichette dati nella raccolta [DataLabelCollection](../../datalabelcollection/) (cioè "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" fa sì che tutti i DataLabels[i].NumberFormat siano uguali a val). 


## Vedi anche

* Classe [String](../../../system/string/)
* Classe [DataLabelFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)