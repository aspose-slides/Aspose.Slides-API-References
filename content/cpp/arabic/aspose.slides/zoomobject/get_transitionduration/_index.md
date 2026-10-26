---
title: get_TransitionDuration()
second_title: Aspose.Slides لمرجع API C++
description: "يحصل على مدة الانتقال بين Zoom و slide. قراءة float. القيمة الافتراضية: 1.0f"
type: docs
weight: 105
url: /ar/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() طريقة


يحصل على مدة الانتقال بين Zoom و slide. قراءة **float**. القيمة الافتراضية: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## ملاحظات


إذا لم يتم تحديدها (TransitionDur = 0)، فستستخدم انتقال الشريحة الهدف والتوقيتات المرتبطة بهذا الانتقال. 

المثال يوضح تغيير مدة الانتقال بين Zoom و slide: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## انظر أيضًا

* فئة [ZoomObject](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)