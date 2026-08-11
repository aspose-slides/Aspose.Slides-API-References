---
title: AddTablePlaceholder()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لاحتواء جدول.
type: docs
weight: 79
url: /ar/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) method

يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لاحتواء جدول.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X للشكل النائب الجديد. |
| y | **float** | إحداثي Y للشكل النائب الجديد. |
| width | **float** | عرض الشكل النائب الجديد. |
| height | **float** | ارتفاع الشكل النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب [Table](../../table/).

## ملاحظات

توضح المثال التالي كيفية إضافة الشكل النائب [Table](../../table/) إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [ILayoutPlaceholderManager](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)