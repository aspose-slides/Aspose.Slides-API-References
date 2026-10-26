---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides برای مرجع API C++
description: یک شکل جای‌گیر جدید را به اسلاید طرح‌بندی اضافه می‌کند تا محتوا، مانند تصویر، جدول، رسانه یا متن را در جهت عمودی نگه دارد.
type: docs
weight: 14
url: /fa/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) متد

یک شکل جای‌گیر جدید را به اسلاید طرح‌بندی اضافه می‌کند تا محتوا، مانند تصویر، جدول، رسانه یا متن را در جهت عمودی نگه دارد.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل جای‌گیر جدید. |
| y | **float** | مختصات Y شکل جای‌گیر جدید. |
| width | **float** | عرض شکل جای‌گیر جدید. |
| height | **float** | ارتفاع شکل جای‌گیر جدید. |

### مقدار بازگشتی

[IAutoShape](../../iautoshape/) ایجاد شد با یک جای‌گیر محتوا (عمودی).

## توضیحات

مثال زیر نشان می‌دهد که چگونه شکل جای‌گیر محتوا (عمودی) را به اسلاید طرح‌بندی اضافه کنید. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [ILayoutPlaceholderManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)