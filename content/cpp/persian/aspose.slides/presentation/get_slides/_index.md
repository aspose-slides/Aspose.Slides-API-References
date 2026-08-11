---
title: get_Slides()
second_title: مرجع API Aspose.Slides برای C++
description: یک لیست از تمام اسلایدهایی که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط‌خواندنی ISlideCollection.
type: docs
weight: 53
url: /fa/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() متد

یک لیست از تمام اسلایدهایی که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط‌خواندنی [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## توضیحات

مثال زیر نشان می‌دهد چگونه رنگ پس‌زمینه اسلایدهای PowerPoint را تنظیم کنید [Presentation](../). 
```cpp
// نمونه‌سازی کلاس Presentation که فایل ارائه را نمایش می‌دهد
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Set the background color of the first ISlide to Blue
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
مثال زیر نشان می‌دهد چگونه تصویر پس‌زمینه اسلایدهای PowerPoint را تنظیم کنید [Presentation](../). 
```cpp
// نمونه‌سازی کلاس Presentation که فایل ارائه را نشان می‌دهد
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// پس‌زمینه را با تصویر تنظیم کنید
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// تنظیم تصویر
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// افزودن تصویر به مجموعه تصاویر ارائه
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// نوشتن ارائه در دیسک
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
مثال زیر نشان می‌دهد چگونه انتقال اسلاید را اضافه کنید [Presentation](../). 
```cpp
// نمونه‌سازی کلاس Presentation برای بارگذاری فایل ارائه منبع
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Apply circle type transition on slide 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Apply comb type transition on slide 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Write the presentation to disk
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
مثال زیر نشان می‌دهد چگونه انتقال پیشرفته اسلاید را اضافه کنید. 
```cpp
// نمونه‌سازی کلاس Presentation که یک فایل ارائه را نمایندگی می‌کند
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// اعمال انتقال دایره‌ای بر اسلاید 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// تنظیم زمان انتقال به 3 ثانیه
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// اعمال انتقال شانه‌ای بر اسلاید 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// تنظیم زمان انتقال به 5 ثانیه
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// اعمال انتقال زوم بر اسلاید 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// تنظیم زمان انتقال به 7 ثانیه
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// نوشتن ارائه به دیسک
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlideCollection](../../islidecollection/)
* کلاس [Presentation](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)