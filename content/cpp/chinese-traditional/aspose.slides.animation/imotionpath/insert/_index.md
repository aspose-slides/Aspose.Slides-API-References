---
title: Insert()
second_title: Aspose.Slides C++ API 參考
description: 在路徑中插入新指令
type: docs
weight: 27
url: /zh-hant/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method

在路徑中插入新指令

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 插入指令的索引 **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | 動畫運動效果行為的指令類型 [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | 點陣列 [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | 動畫運動路徑中點的類型 [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | 指示是否使用相對座標 **bool** |

## 相關參考

* 列舉 [MotionCommandPathType](../../motioncommandpathtype/)
* 列舉 [MotionPathPointsType](../../motionpathpointstype/)
* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [IMotionPath](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)