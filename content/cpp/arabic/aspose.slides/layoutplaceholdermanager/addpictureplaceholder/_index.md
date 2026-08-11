---
title: AddPicturePlaceholder()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يضيف شكلاً نائبًا جديدًا إلى شريحة التخطيط لحفظ صورة.
type: docs
weight: 53
url: /ar/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) طريقة

يضيف شكلاً نائبا جديدًا إلى شريحة التخطيط لاحتواء صورة.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| x | **float** | إحداثي X للشكلة النائبة الجديدة. |
| y | **float** | إحداثي Y للشكلة النائبة الجديدة. |
| width | **float** | عرض الشكلة النائبة الجديدة. |
| height | **float** | ارتفاع الشكلة النائبة الجديدة. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع نائب [Picture](../../picture/).

## ملاحظات

يوضح المثال التالي كيفية إضافة شكلة النائب [Picture](../../picture/) إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## راجع أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [LayoutPlaceholderManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)