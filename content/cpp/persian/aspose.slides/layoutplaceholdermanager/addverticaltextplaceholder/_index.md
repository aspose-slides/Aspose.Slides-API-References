---
title: AddVerticalTextPlaceholder()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل جای‌دار جدید به اسلاید چیدمان اضافه می‌کند تا محتوای متن را در جهت عمودی نگه دارد.
type: docs
weight: 40
url: /fa/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) متد

یک شکل جای‌دار جدید به اسلاید چیدمان اضافه می‌کند تا محتویات متن را در جهت عمودی نگه دارد.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل جای‌دار جدید. |
| y | **float** | مختصات Y شکل جای‌دار جدید. |
| width | **float** | عرض شکل جای‌دار جدید. |
| height | **float** | ارتفاع شکل جای‌دار جدید. |

### مقدار بازگشت

یک [IAutoShape](../../iautoshape/) با جای‌دار Text (Vertical) ایجاد شد.

## یادداشت‌ها

مثال زیر نشان می‌دهد که چگونه شکل جای‌دار Text (Vertical) را به اسلاید چیدمان اضافه کنید.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [LayoutPlaceholderManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)