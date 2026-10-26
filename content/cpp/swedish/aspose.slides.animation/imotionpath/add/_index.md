---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till ett nytt kommando till sökvägen
type: docs
weight: 14
url: /sv/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method


Lägg till ett nytt kommando till sökvägen

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Typ av kommando för animeringsrörelseeffektbeteende [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Punktarray [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Typ av punkter i animeringsrörelsesökväg [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Anger om relativa koordinater ska användas eller inte **bool** |

### Returvärde

Kommando för en sökväg [IMotionCmdPath](../../imotioncmdpath/)

## Se också

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IMotionCmdPath](../../imotioncmdpath/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [IMotionPath](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)