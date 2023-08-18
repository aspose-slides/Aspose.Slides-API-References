---
title: Insert()
second_title: Aspose.Slides for C++ API Reference
description: Insert new command to path
type: docs
weight: 27
url: /aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method


Insert new command to path

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index for command insertion **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Type of command for animation motion effect behavior [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Points array [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Type of points in animation motion path [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indicates whether to use relative coordinates or not **bool** |

## See Also

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [IMotionPath](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)