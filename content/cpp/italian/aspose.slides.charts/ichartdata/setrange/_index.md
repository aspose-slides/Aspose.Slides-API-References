---
title: SetRange()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta l'intervallo dei dati del grafico. Le serie e le categorie verranno aggiornate in base al nuovo intervallo dei dati. Se il numero di serie nell'intervallo dei dati è maggiore del conteggio delle serie nei dati del grafico, verranno aggiunte serie aggiuntive con lo stesso tipo dell'ultima serie nella collezione corrente alla fine della collezione.
type: docs
weight: 157
url: /it/aspose.slides.charts/ichartdata/setrange/
---
## IChartData::SetRange(System::String) metodo


Imposta l'intervallo dei dati del grafico. Le serie e le categorie saranno aggiornate in base al nuovo intervallo dei dati. Se la quantità di serie nell'intervallo dei dati è maggiore del conteggio delle serie nei dati del grafico, verranno aggiunte serie aggiuntive con lo stesso tipo dell'ultima serie nella collezione corrente alla fine della collezione.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetRange(System::String formula)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | La formula dell'intervallo di dati delle celle. Per esempio: \"Sheet1!$A$1:$C$4\" , \"SomeSheetName!A1:B100\", \"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5\". |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)