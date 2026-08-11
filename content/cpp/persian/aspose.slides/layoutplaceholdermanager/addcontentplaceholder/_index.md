---
title: AddContentPlaceholder()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل نگهدارنده جدید به اسلاید طرح اضافه می‌کند تا محتوا مانند تصویر، جدول، رسانه یا متن را نگهداری کند.
type: docs
weight: 1
url: /fa/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) متد

یک شکل نگهدارنده جدید به اسلاید طرح اضافه می‌کند تا محتوا مانند تصویر، جدول، رسانه یا متن را نگهداری کند.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل نگهدارنده جدید. |
| y | **float** | مختصات Y شکل نگهدارنده جدید. |
| width | **float** | عرض شکل نگهدارنده جدید. |
| height | **float** | ارتفاع شکل نگهدارنده جدید. |

### مقدار بازگشت

یک [IAutoShape](../../iautoshape/) با نگهدارنده محتوا ایجاد شد.

## یادداشت‌ها

مثال زیر نشان می‌دهد چگونه شکل نگهدارنده محتوا را به اسلاید طرح اضافه کنیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)