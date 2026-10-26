---
title: AddChartPlaceholder()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل جای‌نگهدارنده جدید به اسلاید قالب اضافه می‌کند تا یک نمودار را نگه دارد.
type: docs
weight: 66
url: /fa/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) متد

Adds a new placeholder shape to the layout slide to hold a chart.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل جای‌نگهدارندهٔ جدید. |
| y | **float** | مختصات Y شکل جای‌نگهدارندهٔ جدید. |
| width | **float** | عرض شکل جای‌نگهدارندهٔ جدید. |
| height | **float** | ارتفاع شکل جای‌نگهدارندهٔ جدید. |

### مقدار برگشتی

یک [IAutoShape](../../iautoshape/) با یک Chart placeholder ایجاد شد.

## توضیحات

مثال زیر نشان می‌دهد چگونه شکل placeholder Chart را به اسلاید طرح اضافه کنیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)