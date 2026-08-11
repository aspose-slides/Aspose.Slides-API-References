---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شکل نگهدارنده جدید به اسلاید قالب اضافه می‌کند تا محتوای متنی را در جهت عمودی نگهداری کند.
type: docs
weight: 40
url: /fa/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) متد


یک شکل نگهدارنده جدید به اسلاید قالب اضافه می‌کند تا محتویات متن را در جهت عمودی نگهداری کند.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل نگهدارنده جدید. |
| y | **float** | مختصات Y شکل نگهدارنده جدید. |
| width | **float** | عرض شکل نگهدارنده جدید. |
| height | **float** | ارتفاع شکل نگهدارنده جدید. |

### مقدار برگشتی

[IAutoShape](../../iautoshape/) ایجاد شد با یک نگهدارنده متن (عمودی).
## ملاحظات



مثال زیر نشان می‌دهد چگونه شکل نگهدارنده متن (عمودی) را به اسلاید قالب اضافه کنیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [ILayoutPlaceholderManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)