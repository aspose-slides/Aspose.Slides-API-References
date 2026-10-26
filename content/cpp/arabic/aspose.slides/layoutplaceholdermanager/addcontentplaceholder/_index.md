---
title: AddContentPlaceholder()
second_title: Aspose.Slides لـ C++ مرجع API
description: يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لحمل المحتوى، مثل صورة أو جدول أو وسائط أو نص.
type: docs
weight: 1
url: /ar/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) طريقة

يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لحمل المحتوى، مثل صورة أو جدول أو وسائط أو نص.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X للشكل النائب الجديد. |
| y | **float** | إحداثي Y للشكل النائب الجديد. |
| width | **float** | عرض الشكل النائب الجديد. |
| height | **float** | ارتفاع الشكل النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب للمحتوى.

## ملاحظات

المثال التالي يوضح كيفية إضافة شكل Content placeholder إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [LayoutPlaceholderManager](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)