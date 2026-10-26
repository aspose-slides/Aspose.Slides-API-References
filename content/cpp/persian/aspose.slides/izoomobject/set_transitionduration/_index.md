---
title: set_TransitionDuration()
second_title: Aspose.Slides برای مرجع API C++
description: "مدت زمان انتقال بین Zoom و slide را تنظیم می‌کند. مقدار float را بنویسید. مقدار پیش‌فرض: 1.0f"
type: docs
weight: 118
url: /fa/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) متد

مدت زمان انتقال بین Zoom و اسلاید را تنظیم می‌کند. **float** بنویسید. مقدار پیش‌فرض: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## یادداشت‌ها

اگر مشخص نشود (TransitionDur = 0)، از انتقال اسلاید مقصد و زمان‌بندی‌های مرتبط با آن استفاده می‌شود. 

مثال نشان می‌دهد که چگونه مدت زمان انتقال بین Zoom و اسلاید را تغییر دهیم: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## موارد مرتبط

* کلاس [IZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)