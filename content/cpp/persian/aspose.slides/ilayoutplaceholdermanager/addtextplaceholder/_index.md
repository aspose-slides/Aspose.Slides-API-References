---
title: AddTextPlaceholder()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل جای‌نگهدار جدید به اسلاید قالب اضافه می‌کند تا محتوی متن را در بر بگیرد.
type: docs
weight: 27
url: /fa/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) متد

یک شکل جای‌نگهدار جدید به اسلاید قالب اضافه می‌کند تا محتوی متن را در بر بگیرد.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل جای‌نگهدار جدید. |
| y | **float** | مختصات Y شکل جای‌نگهدار جدید. |
| width | **float** | عرض شکل جای‌نگهدار جدید. |
| height | **float** | ارتفاع شکل جای‌نگهدار جدید. |

### مقدار بازگشتی

[IAutoShape](../../iautoshape/) ایجاد شد با یک جای‌نگهدار متن.

## توضیحات

مثال زیر نشان می‌دهد که چگونه شکل جای‌نگهدار متن را به اسلاید قالب اضافه کنیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## مباحث مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [ILayoutPlaceholderManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)