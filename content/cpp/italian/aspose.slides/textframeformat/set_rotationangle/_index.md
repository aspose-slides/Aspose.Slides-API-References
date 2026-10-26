---
title: set_RotationAngle()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica una rotazione personalizzata che viene applicata al testo all'interno della casella di delimitazione. Se non è specificata, viene utilizzata la rotazione della forma associata. Se è specificata, allora questa viene applicata indipendentemente dalla forma. Cioè, la forma può avere una rotazione applicata in aggiunta a quella del testo stesso, che ha anch'essa una rotazione applicata. Il valore risultante della rotazione visiva del testo, ricavato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Scrivi float.
type: docs
weight: 313
url: /it/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) metodo

Specifica una rotazione personalizzata che viene applicata al testo all'interno della casella di delimitazione. Se non è specificata, viene utilizzata la rotazione della forma associata. Se è specificata, allora questa viene applicata indipendentemente dalla forma. Cioè, la forma può avere una rotazione applicata oltre a quella del testo stesso, che viene anch'essa ruotata. Il valore risultante della rotazione visiva del testo, ricavato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Scrivi **float**.

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## Osservazioni

Considera il caso in cui una forma abbia una rotazione di 90 gradi in senso orario applicata. In aggiunta, il corpo del testo stesso ha una rotazione di -90 gradi in senso antiorario applicata. Allora la forma risultante sembrerebbe ruotata, ma il testo al suo interno apparirebbe come se non fosse stato ruotato affatto. 

## Vedi anche

* Classe [TextFrameFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)