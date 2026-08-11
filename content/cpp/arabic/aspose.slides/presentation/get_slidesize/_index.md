---
title: get_SlideSize()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يرجع كائن حجم الشريحة. للقراءة فقط ISlideSize.
type: docs
weight: 79
url: /ar/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() طريقة

يُرجِع كائن حجم الشريحة. للقراءة فقط [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## ملاحظات

يُظهر المثال التالي كيفية تغيير حجم الشريحة في PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
يُظهر المثال التالي كيفية ضبط حجم الشريحة بما يتناسب مع مقياس المحتوى لبرنامج PowerPoint [Presentation](../). 
```cpp
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// ضبط حجم الشريحة للعروض المُنشأة ليكون كحجم المصدر
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// يُستخدم الأسلوب SetSize لضبط حجم الشريحة مع تحجيم المحتوى لضمان الملاءمة
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// يُستخدم الأسلوب SetSize لضبط حجم الشريحة مع تكبير حجم المحتوى
// حفظ العرض التقديمي إلى القرص
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
يُظهر المثال التالي طريقة تحديد أحجام شرائح مخصصة في PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// حجم ورق A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISlideSize](../../islidesize/)
* فئة [Presentation](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)