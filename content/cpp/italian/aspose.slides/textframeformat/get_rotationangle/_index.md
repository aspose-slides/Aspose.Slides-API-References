---
title: get_RotationAngle()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la rotazione personalizzata che viene applicata al testo all'interno del riquadro delimitante. Se non è specificata, viene utilizzata la rotazione della forma associata. Se è specificata, allora questa viene applicata indipendentemente dalla forma. Ciò significa che la forma può avere una rotazione applicata in aggiunta alla rotazione applicata al testo stesso. Il valore risultante della rotazione visiva del testo è riassunto da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Leggi float.
type: docs
weight: 300
url: /it/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() metodo


Specifica la rotazione personalizzata che viene applicata al testo all'interno del riquadro delimitante. Se non è specificata, viene utilizzata la rotazione della forma associata. Se è specificata, allora questa viene applicata indipendentemente dalla forma. Cioè la forma può avere una rotazione applicata in aggiunta alla rotazione applicata al testo stesso. Il valore risultante della rotazione visiva del testo è riepilogato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Leggi **float**.

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## Osservazioni


Considera il caso in cui una forma abbia una rotazione di 90 gradi in senso orario applicata ad essa. Inoltre, il corpo del testo stesso ha una rotazione di -90 gradi in senso antiorario applicata ad esso. Allora la forma risultante sembrerebbe ruotata, ma il testo al suo interno apparirebbe come se non fosse stato ruotato affatto. 
## Vedi anche

* Classe [TextFrameFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)