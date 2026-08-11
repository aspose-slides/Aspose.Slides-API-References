---
title: Insert()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إدراج أمر جديد إلى المسار
type: docs
weight: 27
url: /ar/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) الطريقة

إدراج أمر جديد إلى المسار

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس لإدراج الأمر **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | نوع الأمر لتأثير حركة الرسوم المتحركة [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | مصفوفة النقاط [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | نوع النقاط في مسار حركة الرسوم المتحركة [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | يشير إلى ما إذا كان يجب استخدام الإحداثيات النسبية أم لا **bool** |

## انظر أيضاً

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [PointF](../../../system.drawing/pointf/)
* الفئة [IMotionPath](../)
* المجال [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)