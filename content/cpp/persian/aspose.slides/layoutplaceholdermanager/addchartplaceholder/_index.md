---
title: AddChartPlaceholder()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل جای‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک نمودار نگهداری شود.
type: docs
weight: 66
url: /fa/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) متد

یک شکل جای‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک Chart را نگه دارد.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل جای‌گیر جدید. |
| y | **float** | مختصات Y شکل جای‌گیر جدید. |
| width | **float** | عرض شکل جای‌گیر جدید. |
| height | **float** | ارتفاع شکل جای‌گیر جدید. |

### مقدار بازگشتی

[IAutoShape](../../iautoshape/) ایجاد شد که شامل یک Chart جای‌گیر است.

## ملاحظات

مثال زیر نشان می‌دهد چگونه شکل جای‌گیر Chart را به اسلاید طرح‌بندی اضافه کنیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [LayoutPlaceholderManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)