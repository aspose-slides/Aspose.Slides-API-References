---
title: Insert()
second_title: Aspose.Slides per C++ Riferimento API
description: Inserisci un nuovo comando nel percorso
type: docs
weight: 27
url: /it/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) metodo


Inserisci un nuovo comando nel percorso

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice per l'inserimento del comando **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Tipo di comando per il comportamento dell'effetto di movimento dell'animazione [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Array di punti [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Tipo di punti nel percorso di movimento dell'animazione [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indica se utilizzare coordinate relative o meno **bool** |

## Vedi anche

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IMotionPath](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)