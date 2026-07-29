---
title: Insert()
second_title: Aspose.Slides för C++ API-referens
description: Infoga nytt kommando till sökvägen
type: docs
weight: 27
url: /sv/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) metod

Infoga nytt kommando till sökvägen

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för kommandoinsättning **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Typ av kommando för animationsrörelseeffektbeteende [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Punktarray [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Typ av punkter i animationsrörelsekurs [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indikerar om relativa koordinater ska användas eller inte **bool** |

## Se även

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [PointF](../../../system.drawing/pointf/)
* Klass [IMotionPath](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)