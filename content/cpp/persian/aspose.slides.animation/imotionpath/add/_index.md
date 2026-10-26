---
title: Add()
second_title: مستندات API Aspose.Slides برای C++
description: دست فرمان جدیدی به مسیر اضافه می‌کند
type: docs
weight: 14
url: /fa/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) متد


دست فرمان جدیدی به مسیر اضافه می‌کند

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | نوع فرمان برای رفتار اثر حرکت انیمیشن [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | آرایه نقاط [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | نوع نقاط در مسیر حرکت انیمیشن [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | نشان می‌دهد که آیا مختصات نسبی استفاده شود یا نه **bool** |

### مقدار بازگشت

دستور مسیر [IMotionCmdPath](../../imotioncmdpath/)

## موارد مرتبط

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [IMotionCmdPath](../../imotioncmdpath/)
* کلاس [PointF](../../../system.drawing/pointf/)
* کلاس [IMotionPath](../)
* فضای نام [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)