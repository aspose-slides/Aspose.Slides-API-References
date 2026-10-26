---
title: AddTextPlaceholder()
second_title: Aspose.Slides لـ C++ مرجع API
description: يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لحفظ محتوى النص.
type: docs
weight: 27
url: /ar/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) طريقة


يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لحفظ محتوى النص.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```


### المعلمات

| معلمة | نوع | وصف |
| --- | --- | --- |
| x | **float** | الإحداثي X للشكل النائب الجديد. |
| y | **float** | الإحداثي Y للشكل النائب الجديد. |
| width | **float** | عرض الشكل النائب الجديد. |
| height | **float** | ارتفاع الشكل النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب Text.
## ملاحظات



يوضح المثال التالي كيفية إضافة شكل عنصر نائب Text إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [ILayoutPlaceholderManager](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)