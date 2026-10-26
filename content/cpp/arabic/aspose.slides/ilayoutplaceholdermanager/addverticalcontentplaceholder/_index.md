---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides لمرجع API C++
description: يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص في اتجاه عمودي.
type: docs
weight: 14
url: /ar/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) طريقة

يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص في اتجاه عمودي.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X للشكل النائب الجديد. |
| y | **float** | إحداثي Y للشكل النائب الجديد. |
| width | **float** | عرض الشكل النائب الجديد. |
| height | **float** | ارتفاع الشكل النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب Content (Vertical).

## ملاحظات

المثال التالي يوضح كيفية إضافة شكل نائب Content (Vertical) إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [ILayoutPlaceholderManager](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)