---
title: Add()
second_title: Aspose.Slides สำหรับ API อ้างอิง C++
description: เพิ่มคำสั่งใหม่ไปยังเส้นทาง
type: docs
weight: 14
url: /th/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) เมธอด


เพิ่มคำสั่งใหม่ไปยังเส้นทาง

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | ประเภทของคำสั่งสำหรับการทำเอฟเฟกต์การเคลื่อนที่ของแอนิเมชัน [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | อาร์เรย์ของจุด [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | ประเภทของจุดในเส้นทางการเคลื่อนที่ของแอนิเมชัน [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | บ่งชี้ว่าจะใช้พิกัดสัมพัทธ์หรือไม่ **bool** |

### ค่าที่คืนกลับ

คำสั่งของเส้นทาง [IMotionCmdPath](../../imotioncmdpath/)

## ดูเพิ่มเติม

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IMotionCmdPath](../../imotioncmdpath/)
* คลาส [PointF](../../../system.drawing/pointf/)
* คลาส [IMotionPath](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)