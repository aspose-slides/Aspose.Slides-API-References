---
title: set_TransitionDuration()
second_title: مرجع API Aspose.Slides برای C++
description: "مدت زمان انتقال بین زوم و اسلاید را تنظیم می‌کند. مقدار float بنویسید. مقدار پیش‌فرض: 1.0f"
type: docs
weight: 118
url: /fa/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) متد

مدت زمان انتقال بین زوم و اسلاید را تنظیم می‌کند. **float** بنویسید. مقدار پیش‌فرض: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## توضیح

اگر مشخص نشود (TransitionDur = 0)، انتقال اسلاید مقصد و زمان‌بندی‌های مرتبط با آن انتقال استفاده خواهد شد.

مثال نشان می‌دهد که چگونه مدت زمان انتقال بین زوم و اسلاید را تغییر دهید:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## موارد مرتبط

* کلاس [ZoomObject](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)