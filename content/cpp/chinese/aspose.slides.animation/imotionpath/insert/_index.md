---
title: Insert()
second_title: Aspose.Slides for C++ API 参考
description: 向路径插入新命令
type: docs
weight: 27
url: /zh/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method


向路径插入新命令

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 用于插入命令的索引 **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | 动画运动效果行为的命令类型 [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | 点阵列 [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | 动画运动路径中点的类型 [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | 指示是否使用相对坐标 **bool** |

## 参见

* 枚举 [MotionCommandPathType](../../motioncommandpathtype/)
* 枚举 [MotionPathPointsType](../../motionpathpointstype/)
* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类 [PointF](../../../system.drawing/pointf/)
* 类 [IMotionPath](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)