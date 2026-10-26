---
title: AddTextPlaceholder()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضيف شكل عنصر نائب جديد إلى شريحة التخطيط لحمل محتوى النص.
type: docs
weight: 27
url: /ar/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) الطريقة

يضيف شكل عنصر نائب جديد إلى شريحة التخطيط ليحمل محتوى النص.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| x | **float** | إحداثي X لشكل العنصر النائب الجديد. |
| y | **float** | إحداثي Y لشكل العنصر النائب الجديد. |
| width | **float** | عرض شكل العنصر النائب الجديد. |
| height | **float** | ارتفاع شكل العنصر النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب Text.

## ملاحظات

يوضح المثال التالي كيفية إضافة شكل عنصر نائب Text إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [LayoutPlaceholderManager](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)