---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Add new command to path
type: docs
weight: 14
url: /aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method


Add new command to path

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Type of command for animation motion effect behavior [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Points array [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Type of points in animation motion path [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indicates whether to use relative coordinates or not **bool** |

### Return Value

Command of a path [IMotionCmdPath](../../imotioncmdpath/)

## See Also

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IMotionCmdPath](../../imotioncmdpath/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [IMotionPath](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)