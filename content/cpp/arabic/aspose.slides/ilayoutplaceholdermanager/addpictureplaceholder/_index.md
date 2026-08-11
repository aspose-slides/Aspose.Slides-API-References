---
title: AddPicturePlaceholder()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء صورة.
type: docs
weight: 53
url: /ar/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) طريقة

يضيف شكل عنصر نائب جديد إلى شريحة التخطيط لاحتواء صورة.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X للشكل العنصر النائب الجديد. |
| y | **float** | إحداثي Y للشكل العنصر النائب الجديد. |
| width | **float** | عرض الشكل العنصر النائب الجديد. |
| height | **float** | ارتفاع الشكل العنصر النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب [Picture](../../picture/).

## ملاحظات

يوضح المثال التالي كيفية إضافة شكل العنصر النائب [Picture](../../picture/) إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [ILayoutPlaceholderManager](../)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)