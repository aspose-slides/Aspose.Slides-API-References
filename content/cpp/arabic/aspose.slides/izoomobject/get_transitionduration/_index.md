---
title: get_TransitionDuration()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يحصل على مدة الانتقال بين Zoom و slide. قراءة float. القيمة الافتراضية: 1.0f"
type: docs
weight: 105
url: /ar/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() طريقة

يحصل على مدة الانتقال بين Zoom و slide. قراءة **float**. القيمة الافتراضية: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## ملاحظات

إذا لم يتم تحديده (TransitionDur = 0)، فسيتم استخدام انتقال الشريحة الوجهة والتوقيتات المرتبطة بهذا الانتقال.

المثال يوضح تغيير مدة الانتقال بين Zoom و slide:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## انظر أيضًا

* الفئة [IZoomObject](../)
* النطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)