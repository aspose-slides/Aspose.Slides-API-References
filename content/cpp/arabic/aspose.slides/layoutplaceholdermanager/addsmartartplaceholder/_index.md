---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides لـ C++ دليل مرجع API
description: يضيف شكلاً نائبةً جديدًا إلى شريحة التخطيط لحمل مخطط SmartArt.
type: docs
weight: 92
url: /ar/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) طريقة

يضيف شكلاً نائبةً جديدًا إلى شريحة التخطيط لحمل مخطط [SmartArt](../../../aspose.slides.smartart/).

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```

### المعاملات

| معاملة | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X للشكل النائب الجديد. |
| y | **float** | إحداثي Y للشكل النائب الجديد. |
| width | **float** | عرض الشكل النائب الجديد. |
| height | **float** | ارتفاع الشكل النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع نائبة [SmartArt](../../../aspose.slides.smartart/).

## ملاحظات

يوضح المثال التالي كيفية إضافة الشكل النائب [SmartArt](../../../aspose.slides.smartart/) إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IAutoShape](../../iautoshape/)
* الفئة [LayoutPlaceholderManager](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)