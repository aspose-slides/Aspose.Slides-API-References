---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides برای مرجع API C++
description: یک شکل نگهدارنده جدید به اسلاید چیدمان اضافه می‌کند تا محتوا، مانند تصویر، جدول، رسانه یا متن را به صورت عمودی نگه دارد.
type: docs
weight: 14
url: /fa/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) متد

یک شکل نگهدارنده جدید به اسلاید چیدمان اضافه می‌کند تا محتوا، مانند تصویر، جدول، رسانه یا متن را به صورت عمودی نگه دارد.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | مختصات X شکل نگهدارنده جدید. |
| y | **float** | مختصات Y شکل نگهدارنده جدید. |
| width | **float** | عرض شکل نگهدارنده جدید. |
| height | **float** | ارتفاع شکل نگهدارنده جدید. |

### مقدار بازگشت

یک [IAutoShape](../../iautoshape/) با یک نگهدارنده محتوا (عمودی) ساخته شد.

## ملاحظات

مثال زیر نشان می‌دهد چگونه شکل نگهدارنده محتوا (عمودی) را به اسلاید چیدمان اضافه کنیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [LayoutPlaceholderManager](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)