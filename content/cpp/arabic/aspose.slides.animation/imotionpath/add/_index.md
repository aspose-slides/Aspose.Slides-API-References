---
title: Add()
second_title: Aspose.Slides للـ C++ مرجع API
description: إضافة أمر جديد إلى المسار
type: docs
weight: 14
url: /ar/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) طريقة

إضافة أمر جديد إلى المسار

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | نوع الأمر لتأثير حركة الرسوم المتحركة [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | مصفوفة النقاط [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | نوع النقاط في مسار حركة الرسوم المتحركة [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | يوضح ما إذا كان سيتم استخدام إحداثيات نسبية أم لا **bool** |

### قيمة الإرجاع

أمر لمسار [IMotionCmdPath](../../imotioncmdpath/)

## انظر أيضًا

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [IMotionCmdPath](../../imotioncmdpath/)
* فئة [PointF](../../../system.drawing/pointf/)
* فئة [IMotionPath](../)
* مساحة الاسم [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)