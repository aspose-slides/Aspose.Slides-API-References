---
title: get_TransitionDuration()
second_title: مرجع API Aspose.Slides برای C++
description: "دریافت مدت زمان انتقال بین Zoom و اسلاید. خواندن float. مقدار پیش‌فرض: 1.0f"
type: docs
weight: 105
url: /fa/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() method


دریافت مدت زمان انتقال بین Zoom و اسلاید. خواندن **float**. مقدار پیش‌فرض: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## توضیحات


اگر مشخص نشود (TransitionDur = 0)، از انتقال اسلاید مقصد و زمان‌بندی‌های مرتبط با آن انتقال استفاده خواهد شد. 

مثال نشان می‌دهد که چگونه مدت زمان انتقال بین Zoom و اسلاید را تغییر دهید: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## موارد مرتبط

* کلاس [IZoomObject](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)