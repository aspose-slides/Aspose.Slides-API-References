---
title: Add()
second_title: Aspose.Slides for C++ API 參考文件
description: 在路徑中新增指令
type: docs
weight: 14
url: /zh-hant/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method

在路徑中新增指令

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | 動畫運動效果行為的指令類型 [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | 點陣列 [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | 動畫運動路徑中點的類型 [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | 指示是否使用相對座標 **bool** |

### 傳回值

路徑的指令 [IMotionCmdPath](../../imotioncmdpath/)

## 另請參閱

* 列舉 [MotionCommandPathType](../../motioncommandpathtype/)
* 列舉 [MotionPathPointsType](../../motionpathpointstype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [IMotionCmdPath](../../imotioncmdpath/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [IMotionPath](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 程式庫 [Aspose.Slides](../../../)