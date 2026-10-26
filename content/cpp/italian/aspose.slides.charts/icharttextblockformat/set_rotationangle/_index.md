---
title: set_RotationAngle()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la rotazione personalizzata che viene applicata al testo all'interno della cornice di delimitazione. Se non specificato, viene utilizzata la rotazione della forma associata. Se è specificato, allora viene applicata in modo indipendente dalla forma. Ciò significa che la forma può avere una rotazione applicata in aggiunta alla rotazione applicata al testo stesso. Il valore risultante della rotazione visiva del testo, sintetizzato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Scrivi float.
type: docs
weight: 248
url: /it/aspose.slides.charts/icharttextblockformat/set_rotationangle/
---
## IChartTextBlockFormat::set_RotationAngle(float) metodo


Specifica la rotazione personalizzata che viene applicata al testo all'interno della cornice di delimitazione. Se non specificato, viene utilizzata la rotazione della forma associata. Se è specificato, allora viene applicata in modo indipendente dalla forma. Ciò significa che la forma può avere una rotazione applicata in aggiunta alla rotazione applicata al testo stesso. Il valore risultante della rotazione visiva del testo, sintetizzato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Scrivi **float**.

```cpp
virtual void Aspose::Slides::Charts::IChartTextBlockFormat::set_RotationAngle(float value)=0
```

## Osservazioni


Considera il caso in cui una forma abbia una rotazione di 90 gradi in senso orario applicata. In aggiunta a ciò, il corpo del testo stesso ha una rotazione di -90 gradi in senso antiorario applicata. Allora la forma risultante sembrerebbe ruotata, ma il testo al suo interno apparirebbe come se non fosse stato ruotato affatto. 
## Vedi anche

* Classe [IChartTextBlockFormat](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)