---
title: AddPicturePlaceholder()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل نگهدارندهٔ جدید به اسلاید قالب اضافه می‌کند تا یک تصویر را در خود داشته باشد.
type: docs
weight: 53
url: /fa/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) method

یک شکل نگهدارندهٔ جدید به اسلاید قالب اضافه می‌کند تا یک تصویر را در خود داشته باشد.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل نگهدارندهٔ جدید. |
| y | **float** | مختصات Y شکل نگهدارندهٔ جدید. |
| width | **float** | عرض شکل نگهدارندهٔ جدید. |
| height | **float** | ارتفاع شکل نگهدارندهٔ جدید. |

### مقدار بازگشتی

یک [IAutoShape](../../iautoshape/) ایجاد شد با یک نگهدارندهٔ [Picture](../../picture/).

## توضیحات

مثال زیر نشان می‌دهد که چگونه شکل نگهدارندهٔ [Picture](../../picture/) را به اسلاید قالب اضافه کنید.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)