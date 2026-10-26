---
title: AddContentPlaceholder()
second_title: Aspose.Slides برای مرجع API C++
description: یک شکل نگهدارندهٔ جدید به اسلاید لِی‌اوت اضافه می‌کند تا محتوا، مانند تصویر، جدول، رسانه یا متن، را نگه دارد.
type: docs
weight: 1
url: /fa/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) متد

یک شکل نگهدارنده جدید به اسلاید لُی‌اوت اضافه می‌کند تا محتوا، مانند تصویر، جدول، رسانه یا متن، را نگه دارد.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل نگهدارندهٔ جدید. |
| y | **float** | مختصات Y شکل نگهدارندهٔ جدید. |
| width | **float** | عرض شکل نگهدارندهٔ جدید. |
| height | **float** | ارتفاع شکل نگهدارندهٔ جدید. |

### مقدار بازگشت

یک [IAutoShape](../../iautoshape/) با نگهدارندهٔ محتوا ایجاد شد.

## توضیحات

مثال زیر نشان می‌دهد چگونه شکل نگهدارندهٔ Content را به اسلاید لُی‌اوت اضافه کنیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [ILayoutPlaceholderManager](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)