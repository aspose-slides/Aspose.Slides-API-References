---
title: Add()
second_title: Aspose.Slides for C++ API referencia
description: Új parancs hozzáadása az úthoz
type: docs
weight: 14
url: /hu/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) metódus


Új parancs hozzáadása az úthoz

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Parancs típusa az animációs mozgáseffektus viselkedéséhez [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Pontok tömbje [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Pontok típusa az animációs mozgás útvonalban [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Jelzi, hogy relatív koordinátákat használjon-e vagy sem **bool** |

### Visszatérési érték

Az út parancsa [IMotionCmdPath](../../imotioncmdpath/)

## Lásd még

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [IMotionCmdPath](../../imotioncmdpath/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [IMotionPath](../)
* Névtér [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)