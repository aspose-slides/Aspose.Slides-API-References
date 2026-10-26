---
title: set_TransitionDuration()
second_title: مرجع API ل Aspose.Slides للغة C++
description: "يضبط مدة الانتقال بين Zoom و slide. اكتب float. القيمة الافتراضية: 1.0f"
type: docs
weight: 118
url: /ar/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) طريقة

يضبط مدة الانتقال بين Zoom و slide. اكتب **float**. القيمة الافتراضية: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## ملاحظات

إذا لم يتم تحديدها (TransitionDur = 0)، سيستخدم انتقال الشريحة الوجهة والتوقيتات المرتبطة بهذا الانتقال.

المثال يوضح تغيير مدة الانتقال بين Zoom و slide:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## انظر أيضًا

* الفئة [ZoomObject](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)