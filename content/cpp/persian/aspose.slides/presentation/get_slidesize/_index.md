---
title: get_SlideSize()
second_title: Aspose.Slides برای C++ API مرجع
description: شیء اندازه اسلاید را باز می‌گرداند. فقط خواندنی ISlideSize.
type: docs
weight: 79
url: /fa/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() متد

باز می‌گرداند شیء اندازه اسلاید. فقط خواندنی [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## توضیح

مثال زیر نشان می‌دهد چگونه اندازه اسلاید را در یک PowerPoint [Presentation](../) تغییر دهید. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
مثال زیر نشان می‌دهد چگونه اندازه اسلاید را با در نظر گرفتن مقیاس‌بندی محتوا برای یک PowerPoint [Presentation](../) تنظیم کنید. 
```cpp
// یک شیء Presentation ایجاد کنید که نمایانگر یک فایل ارائه است
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// اندازه اسلاید ارائه‌های تولید شده را برابر با منبع تنظیم کنید
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// متد SetSize برای تنظیم اندازه اسلاید با مقیاس‌گذاری محتوا جهت اطمینان از تناسب استفاده می‌شود
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// متد SetSize برای تنظیم اندازه اسلاید با حداکثر کردن اندازه محتوا استفاده می‌شود
// ارائه را بر روی دیسک ذخیره کنید
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
مثال زیر نشان می‌دهد چگونه اندازه‌های اسلاید سفارشی را در یک PowerPoint [Presentation](../) مشخص کنید. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// اندازه کاغذ A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlideSize](../../islidesize/)
* کلاس [Presentation](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)