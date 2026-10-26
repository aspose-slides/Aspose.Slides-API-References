---
title: AddOnlineImagePlaceholder()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ صورة عبر الإنترنت.
type: docs
weight: 118
url: /ar/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) طريقة

يضيف شكل عنصر نائب جديد إلى شريحة التخطيط لحفظ صورة عبر الإنترنت.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي X لشكل العنصر النائب الجديد. |
| y | **float** | إحداثي Y لشكل العنصر النائب الجديد. |
| width | **float** | عرض شكل العنصر النائب الجديد. |
| height | **float** | ارتفاع شكل العنصر النائب الجديد. |

### قيمة الإرجاع

تم إنشاء [IAutoShape](../../iautoshape/) مع عنصر نائب لصورة عبر الإنترنت.
## ملاحظات

يوضح المثال التالي كيفية إضافة شكل عنصر نائب لصورة عبر الإنترنت إلى شريحة التخطيط. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [ILayoutPlaceholderManager](../)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)