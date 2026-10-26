---
title: Insert()
second_title: مرجع API Aspose.Slides برای C++
description: دستور جدید را به مسیر اضافه کنید
type: docs
weight: 27
url: /fa/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) متد


دستور جدید را به مسیر اضافه کنید

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | شاخص برای افزودن فرمان **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | نوع فرمان برای رفتار افکت حرکت انیمیشن [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | آرایه نقاط [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | نوع نقاط در مسیر حرکت انیمیشن [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | نشان می‌دهد آیا از مختصات نسبی استفاده شود یا خیر **bool** |

## موارد مرتبط

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [IMotionPath](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)