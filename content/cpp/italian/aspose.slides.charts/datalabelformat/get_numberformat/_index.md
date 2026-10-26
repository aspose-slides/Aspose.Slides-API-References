---
title: get_NumberFormat()
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta la stringa di formato per l'oggetto DataLabels. Leggi System::String."
type: docs
weight: 27
url: /it/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() metodo

Rappresenta la stringa di formato per l'oggetto DataLabels. Leggi [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Osservazioni

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Se il genitore di questo oggetto [DataLabelFormat](../) è una collezione [DataLabelCollection](../../datalabelcollection/) di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà NumberFormat per le nuove etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/). Quando questa proprietà viene impostata con un valore, quel valore viene impostato anche per la proprietà NumberFormat di tutte le etichette dati nella collezione [DataLabelCollection](../../datalabelcollection/) (ad esempio \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" fa sì che tutti i DataLabels[i].NumberFormat siano uguali a val).

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [DataLabelFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)