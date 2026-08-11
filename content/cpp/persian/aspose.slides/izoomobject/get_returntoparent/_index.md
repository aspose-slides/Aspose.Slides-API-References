---
title: get_ReturnToParent()
second_title: Aspose.Slides برای C++ – مرجع API
description: "رفتار ناوبری را در اسلایدشو دریافت می‌کند. نوع bool. مقدار پیش‌فرض: false"
type: docs
weight: 27
url: /fa/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() متد

رفتار ناوبری را در اسلایدشو دریافت می‌کند. نوع **bool**. مقدار پیش‌فرض: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## ملاحظات

مقدار صحیح این ویژگی رفتار بازگشت به والد در اسلایدشو را مشخص می‌کند.

مثال:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## مراجع

* کلاس [IZoomObject](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)