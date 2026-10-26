---
title: AddTablePlaceholder()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شکل جای‌نگهدار جدید به اسلاید چیدمان اضافه می‌کند تا یک جدول را نگه دارد.
type: docs
weight: 79
url: /fa/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) متد

یک شکل جای‌نگهدار جدید به اسلاید چیدمان اضافه می‌کند تا یک جدول را نگه دارد.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل جای‌نگهدار جدید. |
| y | **float** | مختصات Y شکل جای‌نگهدار جدید. |
| width | **float** | عرض شکل جای‌نگهدار جدید. |
| height | **float** | ارتفاع شکل جای‌نگهدار جدید. |

### مقدار بازگشتی

یک [IAutoShape](../../iautoshape/) با یک جای‌نگهدار [Table](../../table/) ایجاد شد.

## توضیحات

مثال زیر نشان می‌دهد چگونه شکل جای‌نگهدار [Table](../../table/) را به اسلاید چیدمان اضافه کنید. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [ILayoutPlaceholderManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)