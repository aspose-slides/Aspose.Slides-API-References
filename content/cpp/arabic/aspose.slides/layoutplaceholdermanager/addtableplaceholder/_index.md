---
title: AddTablePlaceholder()
second_title: مرجع API Aspose.Slides للـ C++
description: يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ جدول.
type: docs
weight: 79
url: /ar/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) طريقة

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ جدول.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X للشكل العنصر النائب الجديد. |
| y | **float** | إحداثي Y للشكل العنصر النائب الجديد. |
| width | **float** | عرض الشكل العنصر النائب الجديد. |
| height | **float** | ارتفاع الشكل العنصر النائب الجديد. |

## قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب [Table](../../table/).

## ملاحظات

المثال التالي يوضح كيفية إضافة شكل العنصر النائب [Table](../../table/) إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [LayoutPlaceholderManager](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)