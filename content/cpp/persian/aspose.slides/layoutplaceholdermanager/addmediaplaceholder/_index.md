---
title: AddMediaPlaceholder()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شکل نگهدارنده جدید به اسلاید قالب اضافه می‌کند تا یک شی رسانه‌ای را در خود نگه دارد.
type: docs
weight: 105
url: /fa/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) متد

یک شکل نگهدارنده جدید به اسلاید قالب اضافه می‌کند تا یک شی رسانه‌ای را در خود داشته باشد.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل نگهدارنده جدید. |
| y | **float** | مختصات Y شکل نگهدارنده جدید. |
| width | **float** | عرض شکل نگهدارنده جدید. |
| height | **float** | ارتفاع شکل نگهدارنده جدید. |

### مقدار بازگشت

[IAutoShape](../../iautoshape/) ایجاد شد با یک نگهدارنده رسانه‌ای.

## ملاحظات

مثال زیر نشان می‌دهد چگونه شکل نگهدارنده رسانه‌ای را به اسلاید قالب اضافه کنیم.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [LayoutPlaceholderManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)