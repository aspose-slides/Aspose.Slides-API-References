---
title: set_ReturnToParent()
second_title: Aspose.Slides برای C++ مرجع API
description: "رفتار ناوش را در نمایش اسلاید تنظیم می‌کند. bool بنویسید. مقدار پیش‌فرض: false"
type: docs
weight: 40
url: /fa/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) متد


رفتار ناوش در نمایش اسلاید را تنظیم می‌کند. **bool** بنویسید. مقدار پیش‌فرض: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## توضیحات


مقدار صحیح این ویژگی رفتار بازگشت به والد را در نمایش اسلاید مشخص می‌کند. 

مثال:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## موارد مرتبط

* کلاس [ZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)