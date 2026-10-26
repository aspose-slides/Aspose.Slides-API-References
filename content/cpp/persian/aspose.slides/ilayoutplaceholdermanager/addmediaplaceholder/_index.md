---
title: AddMediaPlaceholder()
second_title: راهنمای API Aspose.Slides برای C++
description: یک شکل placeholder جدید به اسلاید طرح اضافه می‌کند تا یک شیء رسانه را در خود جای دهد.
type: docs
weight: 105
url: /fa/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---
## ILayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) متد

یک شکل جای‌دار جدید به اسلاید چیدمان اضافه می‌کند تا یک شی رسانه‌ای را نگه دارد.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل جای‌دار جدید. |
| y | **float** | مختصات Y شکل جای‌دار جدید. |
| width | **float** | عرض شکل جای‌دار جدید. |
| height | **float** | ارتفاع شکل جای‌دار جدید. |
### مقدار بازگشت

Created [IAutoShape](../../iautoshape/) with a Media placeholder.
## نکات



مثال زیر نشان می‌دهد که چگونه شکل جای‌دار Media را به اسلاید طرح‌بندی اضافه کنید. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## موارد مشابه

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [ILayoutPlaceholderManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)