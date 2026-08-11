---
title: AddMediaPlaceholder()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحمل كائن وسائط.
type: docs
weight: 105
url: /ar/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) طريقة

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحمل كائن وسائط.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X للشكل العنصر النائب الجديد. |
| y | **float** | إحداثي Y للشكل العنصر النائب الجديد. |
| width | **float** | عرض الشكل العنصر النائب الجديد. |
| height | **float** | ارتفاع الشكل العنصر النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب Media.

## ملاحظات

يوضح المثال التالي كيفية إضافة شكل العنصر النائب Media إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IAutoShape](../../iautoshape/)
* الفئة [LayoutPlaceholderManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)