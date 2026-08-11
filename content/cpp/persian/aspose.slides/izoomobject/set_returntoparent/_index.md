---
title: set_ReturnToParent()
second_title: Aspose.Slides برای C++ مرجع API
description: "رفتار ناوبری را در اسلایدشو تنظیم می‌کند. مقدار bool بنویسید. مقدار پیش‌فرض: false"
type: docs
weight: 40
url: /fa/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) متد

رفتار ناوبری را در اسلایدشو تنظیم می‌کند. **bool** بنویسید. مقدار پیش‌فرض: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## توضیحات

مقدار True ویژگی رفتار بازگشت به والد را در اسلایدشو مشخص می‌کند.

مثال:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## موارد مرتبط

* کلاس [IZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)