---
title: AddMediaPlaceholder()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لحمل كائن وسائط.
type: docs
weight: 105
url: /ar/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---
## ILayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) طريقة

يضيف شكل نائب جديد إلى شريحة التخطيط لحمل كائن وسائط.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X لشكل نائب جديد. |
| y | **float** | إحداثي Y لشكل نائب جديد. |
| width | **float** | عرض شكل نائب جديد. |
| height | **float** | ارتفاع شكل نائب جديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع نائب Media.

## ملاحظات

يوضح المثال التالي كيفية إضافة شكل نائب Media إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## أنظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [ILayoutPlaceholderManager](../)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)