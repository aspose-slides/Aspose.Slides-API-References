---
title: AddTextPlaceholder()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل نگهدارنده جدید به اسلاید چیدمان اضافه می‌کند تا محتویات متن را در خود داشته باشد.
type: docs
weight: 27
url: /fa/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) متد

یک شکل نگهدارنده جدید به اسلاید چیدمان اضافه می‌کند تا محتویات متن را در خود داشته باشد.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل نگهدارنده جدید. |
| y | **float** | مختصات Y شکل نگهدارنده جدید. |
| width | **float** | عرض شکل نگهدارنده جدید. |
| height | **float** | ارتفاع شکل نگهدارنده جدید. |

### مقدار بازگشت

یک [IAutoShape](../../iautoshape/) با یک نگهدارنده متن ایجاد شد.
## ملاحظات

مثال زیر نشان می‌دهد چگونه شکل نگهدارنده متن را به اسلاید چیدمان اضافه کنید. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## مراجع دیگر

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [LayoutPlaceholderManager](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)