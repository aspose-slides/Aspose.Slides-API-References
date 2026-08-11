---
title: AddContentPlaceholder()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف شكلاً نقطة وضع جديدة إلى شريحة التخطيط لتخزين المحتوى، مثل صورة أو جدول أو وسائط أو نص.
type: docs
weight: 1
url: /ar/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) طريقة


يضيف شكلاً نقطة وضع جديدة إلى شريحة التخطيط لحمل المحتوى، مثل صورة أو جدول أو وسائط أو نص.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X للشكلة نقطة الوضع الجديدة. |
| y | **float** | إحداثي Y للشكلة نقطة الوضع الجديدة. |
| width | **float** | عرض الشكلة نقطة الوضع الجديدة. |
| height | **float** | ارتفاع الشكلة نقطة الوضع الجديدة. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب محتوى.
## ملاحظات



يوضح المثال التالي كيفية إضافة شكل عنصر نائب المحتوى إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [ILayoutPlaceholderManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)