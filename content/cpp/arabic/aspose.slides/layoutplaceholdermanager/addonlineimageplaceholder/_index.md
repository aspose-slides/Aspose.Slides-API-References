---
title: AddOnlineImagePlaceholder()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف شكلاً نائبيًا جديدًا إلى شريحة التخطيط لاحتواء صورة عبر الإنترنت.
type: docs
weight: 118
url: /ar/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) طريقة

يضيف شكلاً نائبيًا جديدًا إلى شريحة التخطيط لاحتواء صورة عبر الإنترنت.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X للشكل العنصر النائب الجديد. |
| y | **float** | إحداثي Y للشكل العنصر النائب الجديد. |
| width | **float** | عرض الشكل العنصر النائب الجديد. |
| height | **float** | ارتفاع الشكل العنصر النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب لصورة عبر الإنترنت.

## ملاحظات

يوضح المثال التالي كيفية إضافة عنصر نائب صورة عبر الإنترنت إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [LayoutPlaceholderManager](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)