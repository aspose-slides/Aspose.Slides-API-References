---
title: AddChartPlaceholder()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء Chart.
type: docs
weight: 66
url: /ar/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) الطريقة

يضيف شكل عنصر نائب جديد إلى شريحة التخطيط لاحتواء Chart.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X للعنصر النائب الجديد. |
| y | **float** | إحداثي Y للعنصر النائب الجديد. |
| width | **float** | عرض العنصر النائب الجديد. |
| height | **float** | ارتفاع العنصر النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب Chart.

## ملاحظات

يوضح المثال التالي كيفية إضافة شكل عنصر نائب Chart إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [ILayoutPlaceholderManager](../)
* فضاء الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)