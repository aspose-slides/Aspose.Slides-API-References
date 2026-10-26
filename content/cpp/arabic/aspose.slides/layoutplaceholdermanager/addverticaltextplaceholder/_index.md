---
title: AddVerticalTextPlaceholder()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء محتوى النص في اتجاه عمودي.
type: docs
weight: 40
url: /ar/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) طريقة

يضيف شكل عنصر نائب جديد إلى شريحة التخطيط لاحتواء محتوى النص في اتجاه عمودي.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي X للشكل العنصر النائب الجديد. |
| y | **float** | الإحداثي Y للشكل العنصر النائب الجديد. |
| width | **float** | عرض الشكل العنصر النائب الجديد. |
| height | **float** | ارتفاع الشكل العنصر النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب نص (عمودي).

## ملاحظات



يوضح المثال التالي كيفية إضافة شكل عنصر نائب نص (عمودي) إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [LayoutPlaceholderManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)