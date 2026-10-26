---
title: set_RotationAngle()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la rotazione personalizzata che viene applicata al testo all'interno del riquadro delimitante. Se non è specificata, viene utilizzata la rotazione della forma associata. Se è specificata, viene applicata indipendentemente dalla forma. In altre parole, la forma può avere una rotazione applicata in aggiunta alla rotazione del testo stesso. Il valore risultante della rotazione visuale del testo è riepilogato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Scrivi float.
type: docs
weight: 352
url: /it/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) metodo

Specifica la rotazione personalizzata che viene applicata al testo all'interno del riquadro delimitante. Se non è specificata, viene utilizzata la rotazione della forma associata. Se è specificata, viene applicata indipendentemente dalla forma. In altre parole, la forma può avere una rotazione applicata in aggiunta alla rotazione del testo stesso. Il valore risultante della rotazione visuale del testo è riepilogato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Scrivi **float**.

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## Osservazioni

Considera il caso in cui una forma abbia una rotazione di 90 gradi in senso orario applicata a essa. In aggiunta, il corpo del testo stesso ha una rotazione di -90 gradi in senso antiorario applicata a esso. Allora la forma risultante sembrerebbe ruotata, ma il testo al suo interno apparirebbe come se non fosse stato ruotato affatto.

## Vedi anche

* Classe [ITextFrameFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)