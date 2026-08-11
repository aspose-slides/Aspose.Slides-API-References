---
title: AddVerticalContentPlaceholder()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص في الاتجاه العمودي.
type: docs
weight: 14
url: /ar/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) طريقة

يضيف شكل عنصر نائب جديد إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص في الاتجاه العمودي.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | إحداثي X لشكل العنصر النائب الجديد. |
| y | **float** | إحداثي Y لشكل العنصر النائب الجديد. |
| width | **float** | عرض شكل العنصر النائب الجديد. |
| height | **float** | ارتفاع شكل العنصر النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب Content (Vertical).

## ملاحظات

يوضح المثال التالي كيفية إضافة شكل عنصر نائب Content (Vertical) إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [LayoutPlaceholderManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)