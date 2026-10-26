---
title: AddSmartArtPlaceholder()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحمل مخطط SmartArt.
type: docs
weight: 92
url: /ar/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) طريقة

يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحمل مخطط [SmartArt](../../../aspose.slides.smartart/).

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X لشكل العنصر النائب الجديد. |
| y | **float** | إحداثي Y لشكل العنصر النائيب الجديد. |
| width | **float** | عرض شكل العنصر النائب الجديد. |
| height | **float** | ارتفاع شكل العنصر النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب [SmartArt](../../../aspose.slides.smartart/).

## ملاحظات

يوضح المثال التالي كيفية إضافة شكل عنصر نائب [SmartArt](../../../aspose.slides.smartart/) إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [ILayoutPlaceholderManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)