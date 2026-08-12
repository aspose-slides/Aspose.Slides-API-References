---
title: Insert()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกคำสั่งใหม่เข้าสู่เส้นทาง
type: docs
weight: 27
url: /th/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) เมธอด


แทรกคำสั่งใหม่เข้าสู่เส้นทาง

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีสำหรับแทรกคำสั่ง **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | ประเภทของคำสั่งสำหรับพฤติกรรมเอฟเฟกต์การเคลื่อนไหวของอนิเมชัน [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | อาร์เรย์ของจุด [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | ประเภทของจุดในเส้นทางการเคลื่อนที่ของอนิเมชัน [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | บ่งชี้ว่าควรใช้พิกัดเชิงสัมพัทธ์หรือไม่ **bool** |

## ดูเพิ่มเติม

* เอนัม [MotionCommandPathType](../../motioncommandpathtype/)
* เอนัม [MotionPathPointsType](../../motionpathpointstype/)
* ประเภทนิยาม [ArrayPtr](../../../system/arrayptr/)
* คลาส [PointF](../../../system.drawing/pointf/)
* คลาส [IMotionPath](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)