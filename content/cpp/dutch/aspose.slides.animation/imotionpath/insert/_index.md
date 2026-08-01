---
title: Insert()
second_title: Aspose.Slides voor C++ API Referentie
description: Voeg een nieuwe opdracht toe aan het pad
type: docs
weight: 27
url: /nl/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method


Voeg een nieuwe opdracht toe aan het pad

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index voor het invoegen van de opdracht **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Type van opdracht voor animatie bewegings-effect gedrag [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Puntenreeks [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Type van punten in animatie bewegingspad [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Geeft aan of relatieve coördinaten moeten worden gebruikt of niet **bool** |

## Zie ook

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [IMotionPath](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)