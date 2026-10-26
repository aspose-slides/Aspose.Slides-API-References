---
title: AddVerticalTextPlaceholder()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء محتوى النص في اتجاه عمودي.
type: docs
weight: 40
url: /ar/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) طريقة

يضيف شكلاً جديدًا للنص العنصر النائب إلى شريحة التخطيط لاحتواء محتوى النص في اتجاه عمودي.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X لشكل العنصر النائب الجديد. |
| y | **float** | إحداثي Y لشكل العنصر النائب الجديد. |
| width | **float** | عرض شكل العنصر النائب الجديد. |
| height | **float** | ارتفاع شكل العنصر النائب الجديد. |

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

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [ILayoutPlaceholderManager](../)
* النطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)