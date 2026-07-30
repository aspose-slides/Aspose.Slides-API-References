---
title: Add()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiungi nuovo comando al percorso
type: docs
weight: 14
url: /it/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) metodo

Aggiungi nuovo comando al percorso

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Tipo di comando per il comportamento dell'effetto di movimento di animazione [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Array di punti [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Tipo di punti nel percorso di movimento di animazione [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indica se utilizzare coordinate relative o meno **bool** |

### Valore restituito

Comando di un percorso [IMotionCmdPath](../../imotioncmdpath/)

## Vedi anche

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IMotionCmdPath](../../imotioncmdpath/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IMotionPath](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)