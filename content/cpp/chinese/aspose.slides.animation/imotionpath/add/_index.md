---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 向路径添加新命令
type: docs
weight: 14
url: /zh/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) 方法


向路径添加新命令

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | 动画运动效果行为的命令类型 [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | 点数组 [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | 动画运动路径中点的类型 [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | 指示是否使用相对坐标 **bool** |

### 返回值

路径的命令 [IMotionCmdPath](../../imotioncmdpath/)

## 另见

* 枚举 [MotionCommandPathType](../../motioncommandpathtype/)
* 枚举 [MotionPathPointsType](../../motionpathpointstype/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类 [IMotionCmdPath](../../imotioncmdpath/)
* 类 [PointF](../../../system.drawing/pointf/)
* 类 [IMotionPath](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)