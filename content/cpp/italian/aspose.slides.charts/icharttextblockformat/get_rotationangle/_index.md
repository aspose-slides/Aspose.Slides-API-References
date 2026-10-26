---
title: get_RotationAngle()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la rotazione personalizzata che viene applicata al testo all'interno della casella di delimitazione. Se non è specificata, viene utilizzata la rotazione della forma associata. Se è specificata, allora viene applicata in modo indipendente dalla forma. In tal modo la forma può avere una rotazione applicata in aggiunta alla rotazione del testo stesso. Il valore risultante della rotazione visiva del testo è riepilogato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Leggi float.
type: docs
weight: 235
url: /it/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() metodo


Specifica la rotazione personalizzata che viene applicata al testo all'interno della casella di delimitazione. Se non è specificata, viene utilizzata la rotazione della forma associata. Se è specificata, allora viene applicata in modo indipendente dalla forma. In questo modo la forma può avere una rotazione applicata in aggiunta alla rotazione del testo stesso. Il valore risultante della rotazione visiva del testo è riepilogato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Leggi **float**.

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## Osservazioni


Considera il caso in cui una forma abbia una rotazione di 90 gradi in senso orario applicata ad essa. Oltre a ciò, il corpo del testo stesso ha una rotazione di -90 gradi in senso antiorario applicata. Allora la forma risultante sembrerebbe ruotata, ma il testo al suo interno apparirebbe come se non fosse stato ruotato affatto. 
## Vedi anche

* Classe [IChartTextBlockFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)