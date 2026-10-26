---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شکل نگهدارنده جدید به اسلاید چیدمان اضافه می‌کند تا یک تصویر آنلاین را نگه دارد.
type: docs
weight: 118
url: /fa/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) متد

Adds a new placeholder shape to the layout slide to hold an online image.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | مختصات X شکل نگهدارنده جدید. |
| y | **float** | مختصات Y شکل نگهدارنده جدید. |
| width | **float** | عرض شکل نگهدارنده جدید. |
| height | **float** | ارتفاع شکل نگهدارنده جدید. |

### مقدار بازگشتی

یک [IAutoShape](../../iautoshape/) با نگهدارنده تصویر آنلاین ایجاد شد.

## توضیحات

مثال زیر نشان می‌دهد چگونه شکل نگهدارنده تصویر آنلاین را به اسلاید چیدمان اضافه کنید. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)