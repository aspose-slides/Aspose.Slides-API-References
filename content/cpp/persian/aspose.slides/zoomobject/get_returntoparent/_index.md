---
title: get_ReturnToParent()
second_title: مرجع API Aspose.Slides برای C++
description: "رفتار ناوبری در اسلایدشو را دریافت می‌کند. خواندنی bool. مقدار پیش‌فرض: false"
type: docs
weight: 27
url: /fa/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() متد


رفتار ناوبری در اسلایدشو را دریافت می‌کند. خواندنی **bool**. مقدار پیش‌فرض: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## توضیحات


مقدار True ویژگی رفتار بازگشت به والد را در اسلایدشو مشخص می‌کند. 

مثال: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## موارد مرتبط

* کلاس [ZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)