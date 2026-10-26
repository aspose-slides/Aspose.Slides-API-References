---
title: get_TransitionDuration()
second_title: Aspose.Slides برای C++ مرجع API
description: "مدت زمان انتقال بین Zoom و اسلاید را دریافت می‌کند. نوع float. مقدار پیش‌فرض: 1.0f"
type: docs
weight: 105
url: /fa/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() متد

دوره زمان انتقال بین Zoom و اسلاید را دریافت می‌کند. نوع **float**. مقدار پیش‌فرض: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## توضیحات

اگر مشخص نشود (TransitionDur = 0)، از انتقال اسلاید مقصد و زمان‌بندی‌های مرتبط با آن انتقال استفاده می‌شود.

مثال زیر نحوه تغییر مدت زمان انتقال بین Zoom و اسلاید را نشان می‌دهد:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## موارد مرتبط

* کلاس [ZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)