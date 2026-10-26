---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شکل نگهدارنده جدید به اسلاید قالب اضافه می‌کند تا یک تصویر آنلاین را نگه دارد.
type: docs
weight: 118
url: /fa/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) متد


یک شکل نگهدارنده جدید به اسلاید قالب اضافه می‌کند تا یک تصویر آنلاین را نگه دارد.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل نگهدارنده جدید. |
| y | **float** | مختصات Y شکل نگهدارنده جدید. |
| width | **float** | عرض شکل نگهدارنده جدید. |
| height | **float** | ارتفاع شکل نگهدارنده جدید. |

### مقدار بازگشت

یک [IAutoShape](../../iautoshape/) با یک نگهدارنده تصویر آنلاین ایجاد شد.

## توضیحات



مثال زیر نشان می‌دهد چگونه شکل نگهدارنده تصویر آنلاین را به اسلاید قالب اضافه کنیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)