---
title: AddSmartArtPlaceholder()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل جای‌دار جدید به اسلاید طرح اضافه می‌کند تا یک نمودار SmartArt را در خود جای دهد.
type: docs
weight: 92
url: /fa/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) متد

یک شکل جای‌دار جدید به اسلاید طرح اضافه می‌کند تا یک نمودار [SmartArt](../../../aspose.slides.smartart/) را در خود جای دهد.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل جای‌دار جدید. |
| y | **float** | مختصات Y شکل جای‌دار جدید. |
| width | **float** | عرض شکل جای‌دار جدید. |
| height | **float** | ارتفاع شکل جای‌دار جدید. |

### مقدار بازگشتی

یک [IAutoShape](../../iautoshape/) ایجاد شد با یک جای‌دار [SmartArt](../../../aspose.slides.smartart/).

## ملاحظات

مثال زیر نشان می‌دهد چگونه شکل جای‌دار [SmartArt](../../../aspose.slides.smartart/) را به اسلاید طرح اضافه کنیم.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [ILayoutPlaceholderManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)