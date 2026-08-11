---
title: get_Slides()
second_title: Aspose.Slides لـ C++ مرجع API
description: إرجاع قائمة بجميع الشرائح التي تم تعريفها في العرض التقديمي. للقراءة فقط ISlideCollection.
type: docs
weight: 53
url: /ar/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() طريقة


إرجاع قائمة بجميع الشرائح التي تم تعريفها في العرض التقديمي. للقراءة فقط [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## ملاحظات


مثال التالي يوضح كيفية ضبط لون خلفية الشرائح في PowerPoint [Presentation](../). 
```cpp
// إنشاء كائن من الفئة Presentation التي تمثل ملف العرض التقديمي
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Set the background color of the first ISlide to Blue
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
مثال التالي يوضح كيفية ضبط صورة خلفية الشرائح في PowerPoint [Presentation](../). 
```cpp
// إنشاء كائن من الفئة Presentation التي تمثل ملف العرض التقديمي
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// ضبط الخلفية باستخدام صورة
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// ضبط الصورة
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// إضافة الصورة إلى مجموعة صور العرض التقديمي
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// كتابة العرض التقديمي إلى القرص
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
مثال التالي يوضح كيفية إضافة انتقال الشريحة [Presentation](../). 
```cpp
// إنشاء كائن من الفئة Presentation لتحميل ملف العرض التقديمي المصدر
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// تطبيق انتقال من نوع دائرة على الشريحة 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// تطبيق انتقال من نوع مشط على الشريحة 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// كتابة العرض التقديمي إلى القرص
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
مثال التالي يوضح كيفية إضافة انتقال شريحة متقدم. 
```cpp
// إنشاء كائن من الفئة Presentation التي تمثل ملف عرض تقديمي
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// تطبيق انتقال من نوع دائرة على الشريحة 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// ضبط مدة الانتقال إلى 3 ثوانٍ
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// تطبيق انتقال من نوع مشط على الشريحة 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// ضبط مدة الانتقال إلى 5 ثوانٍ
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// تطبيق انتقال من نوع تكبير على الشريحة 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// ضبط مدة الانتقال إلى 7 ثوانٍ
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// كتابة العرض التقديمي إلى القرص
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISlideCollection](../../islidecollection/)
* فئة [Presentation](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)