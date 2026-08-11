---
title: AddPicturePlaceholder()
second_title: Aspose.Slides برای مرجع API C++
description: یک شکل جای‌دار جدید به اسلاید طرح اضافه می‌کند تا تصویر را در خود نگه دارد.
type: docs
weight: 53
url: /fa/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) method

یک شکل جای‌دار جدید به اسلاید طرح اضافه می‌کند تا تصویر را در خود نگه دارد.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | مختصات X شکل جای‌دار جدید. |
| y | **float** | مختصات Y شکل جای‌دار جدید. |
| width | **float** | عرض شکل جای‌دار جدید. |
| height | **float** | ارتفاع شکل جای‌دار جدید. |

### مقدار بازگشت

یک [IAutoShape](../../iautoshape/) با یک جای‌دار [Picture](../../picture/) ایجاد شد.
## توضیحات

مثال زیر نشان می‌دهد چگونه شکل جای‌دار [Picture](../../picture/) را به اسلاید طرح اضافه کنیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [LayoutPlaceholderManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)