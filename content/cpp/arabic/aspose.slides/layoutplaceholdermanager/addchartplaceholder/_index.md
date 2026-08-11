---
title: AddChartPlaceholder()
second_title: مرجع API Aspose.Slides لـ C++
description: يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لاحتواء مخطط.
type: docs
weight: 66
url: /ar/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) طريقة


يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لاحتواء مخطط.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | إحداثي X للشكل النائب الجديد. |
| y | **float** | إحداثي Y للشكل النائب الجديد. |
| width | **float** | عرض الشكل النائب الجديد. |
| height | **float** | ارتفاع الشكل النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع نائبة Chart.
## ملاحظات



المثال التالي يوضح كيفية إضافة شكل نائبة Chart إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [LayoutPlaceholderManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)